# 🚀 Git for DevOps

A comprehensive repository for learning and mastering **Git** and **GitHub** from a DevOps perspective. This repository contains Git fundamentals, branching strategies, collaboration workflows, and hands-on exercises commonly used in real-world DevOps environments.

---

## 📖 About

Version control is one of the most essential skills for every DevOps Engineer. This repository documents my Git learning journey, practical exercises, and real-world Git workflows used in software development and DevOps projects.

Whether you're a beginner or an experienced engineer, this repository serves as a quick reference and practice guide for Git and GitHub.

---

## 🎯 Learning Objectives

After completing this repository, you will be able to:

* Understand Git architecture
* Initialize and manage Git repositories
* Track file changes
* Create meaningful commits
* Work with branches
* Merge branches successfully
* Resolve merge conflicts
* Use GitHub for collaboration
* Manage remote repositories
* Create Pull Requests
* Follow Git best practices in DevOps environments

---

# 📚 Topics Covered

* Git Installation
* Git Configuration
* Git Repository Initialization
* Git Status
* Git Add
* Git Commit
* Git Log
* Git Diff
* Git Branch
* Git Checkout
* Git Switch
* Git Merge
* Git Rebase
* Git Reset
* Git Restore
* Git Stash
* Git Tags
* Git Ignore (.gitignore)
* Git Remote
* Git Clone
* Git Fetch
* Git Pull
* Git Push
* GitHub Basics
* Pull Requests
* Forks
* Merge Conflicts
* Git Branching Strategy
* Git Workflow for DevOps
* Best Practices

---

# 📂 Repository Structure

```text
git_for_devops/
│
├── 01-installation/
├── 02-git-basics/
├── 03-commits/
├── 04-branching/
├── 05-merging/
├── 06-rebasing/
├── 07-remote-repositories/
├── 08-github/
├── 09-gitignore/
├── 10-tags/
├── 11-stash/
├── 12-conflicts/
├── 13-projects/
├── 14-best-practices/
└── README.md
```

---

# 🛠 Prerequisites

Before getting started, ensure you have:

* Basic Linux or Windows command-line knowledge
* Git installed
* A GitHub account
* Visual Studio Code (recommended)

---

# ⚙️ Installation

Clone this repository:

```bash
git clone https://github.com/sammad00/git_for_devops.git
```

Navigate into the project:

```bash
cd git_for_devops
```

Verify Git installation:

```bash
git --version
```

---

# 💻 Frequently Used Git Commands

Initialize a repository:

```bash
git init
```

Check repository status:

```bash
git status
```

Add files:

```bash
git add .
```

Commit changes:

```bash
git commit -m "Initial commit"
```

View commit history:

```bash
git log --oneline
```

Create a new branch:

```bash
git branch feature
```

Switch to a branch:

```bash
git checkout feature
```

Or using the modern command:

```bash
git switch feature
```

Merge a branch:

```bash
git merge feature
```

Pull the latest changes:

```bash
git pull origin main
```

Push changes:

```bash
git push origin main
```

Clone a repository:

```bash
git clone <repository-url>
```

---

# 🌿 Git Branching Workflow

```text
main
 │
 ├── dev
 │     │
 │     ├── feature/login
 │     ├── feature/docker
 │     └── feature/api
 │
 └── hotfix
```

Typical workflow:

1. Create a feature branch from `dev`.
2. Make and commit your changes.
3. Push the feature branch to GitHub.
4. Open a Pull Request.
5. Merge into `dev`.
6. Test changes.
7. Merge `dev` into `main` for production releases.

---

# ✅ Best Practices

* Write clear and descriptive commit messages.
* Commit small, focused changes.
* Pull before pushing to avoid conflicts.
* Use feature branches for new work.
* Keep the `main` branch stable.
* Review Pull Requests before merging.
* Use `.gitignore` to exclude unnecessary files.
* Avoid committing secrets, passwords, or API keys.
* Tag stable releases using Git tags.

---

# 🚀 DevOps Use Cases

Git plays a central role in DevOps by enabling:

* Source Code Management (SCM)
* CI/CD Pipelines
* Infrastructure as Code (IaC)
* Team Collaboration
* Automated Deployments
* Version Tracking
* Release Management
* Change Auditing

---

# 📚 Recommended Learning Path

1. Git Basics
2. Branching
3. Merging
4. GitHub
5. Pull Requests
6. Conflict Resolution
7. Git Rebase
8. Git Tags
9. GitHub Actions
10. CI/CD with Jenkins
11. Docker Integration
12. Kubernetes Deployments

---

# 🤝 Contributing

Contributions are welcome! If you'd like to improve this repository:

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Abdul Sammad**

* DevOps Engineer
* Linux System Administrator
* Docker & Kubernetes Enthusiast
* Passionate about Automation, Cloud Computing, and Open Source

If you found this repository useful, please consider giving it a ⭐ and sharing it with others.

