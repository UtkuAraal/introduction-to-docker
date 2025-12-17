# Introduction to Docker - Training Materials Repository

This repository contains hands-on examples, exercises, and sample projects for learning Docker from beginner to advanced level.

## 📚 Repository Structure

```
introduction-to-docker/
├── examples/                           # Hands-on examples and projects
│   └── docker-cicd-github-actions/    # GitHub Actions CI/CD pipeline example
├── Dockerfiles/                        # Dockerfile examples (if any)
└── README.md                           # This file
```

---

## 🎯 Available Examples

### 1. Docker CI/CD with GitHub Actions

**Location:** [`examples/docker-cicd-github-actions/`](examples/docker-cicd-github-actions/)

**What it demonstrates:**
- Complete GitHub Actions CI/CD pipeline
- Automated Docker image builds
- Testing in containers
- Push to GitHub Container Registry (ghcr.io)
- Automatic version tagging
- Security scanning with Trivy

**Technologies:**
- Docker & Multi-stage builds
- GitHub Actions
- Node.js & Express.js
- GitHub Container Registry

**Quick Start:**
```bash
cd examples/docker-cicd-github-actions
docker build -t demo:local .
docker run -p 3000:3000 demo:local
```

**Documentation:**
- [README](examples/docker-cicd-github-actions/README.md) - Complete setup guide
- [QUICK-START](examples/docker-cicd-github-actions/QUICK-START.md) - 5-minute walkthrough
- [TRAINING-GUIDE](examples/docker-cicd-github-actions/TRAINING-GUIDE.md) - Full workshop guide

---

## 🚀 Getting Started

### Prerequisites

- Docker Desktop installed
- Git installed
- GitHub account (for CI/CD examples)
- Basic command line knowledge

### Clone This Repository

```bash
git clone https://github.com/Emre-Yavas/introduction-to-docker.git
cd introduction-to-docker
```

### Explore Examples

Each example has its own README with:
- ✅ Learning objectives
- ✅ Step-by-step instructions
- ✅ Hands-on exercises
- ✅ Troubleshooting guide
- ✅ Best practices

---

## 📖 Learning Path

**Recommended order:**

1. **Docker Basics** (external resources)
   - Install Docker Desktop
   - Learn basic commands (`run`, `build`, `ps`, `stop`)
   - Understand images and containers

2. **Dockerfile Basics** (external resources)
   - Write your first Dockerfile
   - Understand layers and caching
   - Multi-stage builds

3. **CI/CD with GitHub Actions** ⭐ **Start here!**
   - Go to `examples/docker-cicd-github-actions/`
   - Follow the QUICK-START guide
   - Complete hands-on exercises

---

## 🎓 Who Is This For?

- **Beginners:** Step-by-step guides with detailed explanations
- **Intermediate:** Best practices and real-world patterns
- **DevOps Engineers:** Production-ready CI/CD pipelines
- **Developers:** Integrate Docker into development workflow

---

## 🔧 Technologies Covered

- **Docker:** Containerization, images, multi-stage builds
- **CI/CD:** GitHub Actions, automated workflows
- **Container Registries:** GitHub Container Registry (ghcr.io)
- **Testing:** Running tests in containers
- **Security:** Vulnerability scanning, best practices
- **DevOps:** Automation, deployment strategies

---

## 📝 Contributing

This is a training materials repository. If you find issues or have suggestions:

1. Open an issue
2. Submit a pull request
3. Share feedback

---

## 📚 Additional Resources

**Official Documentation:**
- [Docker Documentation](https://docs.docker.com/)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Docker Best Practices](https://docs.docker.com/develop/dev-best-practices/)

**Online Learning:**
- [Play with Docker](https://labs.play-with-docker.com/)
- [Docker Hub](https://hub.docker.com/)

---

## 📬 Contact

**Repository Owner:** Emre Yavaş
**GitHub:** [@Emre-Yavas](https://github.com/Emre-Yavas)

---

## 📄 License

This repository is for educational purposes. See individual examples for specific licenses.

---

## 🎯 Quick Navigation

- [Docker CI/CD Example →](examples/docker-cicd-github-actions/)
- [Quick Start Guide →](examples/docker-cicd-github-actions/QUICK-START.md)
- [Training Guide →](examples/docker-cicd-github-actions/TRAINING-GUIDE.md)

**Start learning Docker today!** 🚀
