# DevOps Linux Lab

Hands-on Linux and Bash laboratory for building practical DevOps fundamentals through daily exercises, mini projects, troubleshooting, and documentation.

## 🎯 Learning Goals

This repository is used to practice and document Linux skills that are essential for a DevOps engineer.

The main goals are:

- Build strong Linux command-line fundamentals
- Understand Linux filesystem and permissions
- Practice Bash scripting
- Learn process and service management
- Practice networking and troubleshooting
- Work comfortably with Git and GitHub
- Build practical DevOps habits through daily hands-on labs

## 🧰 Environment

The laboratory environment uses:

- WSL Ubuntu
- Bash
- Vim
- Git
- GitHub

## 📚 Learning Path

The Linux laboratory is divided into progressive daily exercises:

| Stage | Topic |
|---|---|
| Day 01 | Linux CLI Fundamentals |
| Day 02 | Linux Filesystem & File Operations |
| Day 03 | Users, Groups & Permissions |
| Day 04 | Processes & System Management |
| Day 05 | Package Management |
| Day 06 | Networking Fundamentals |
| Day 07 | Logs & Troubleshooting |
| Day 08 | Bash Scripting Fundamentals |
| Day 09 | Environment Variables & Shell |
| Day 10 | Linux Mini Project |

The learning path will continue to expand as new DevOps topics are introduced.

## 📁 Repository Structure

```text
devops-linux-lab/
├── day-01/
│   ├── commands.md
│   └── notes.txt
│
├── logbook/
│   └── day-01.md
│
└── README.md
```

## 🧪 Daily Lab Workflow

Each learning day follows a practical workflow:

```text
Learn
  ↓
Practice in Linux
  ↓
Build a small exercise
  ↓
Document commands & results
  ↓
Update Logbook
  ↓
Commit
  ↓
Push Branch
  ↓
Pull Request
  ↓
Review
  ↓
Merge to main
```

## 📝 Documentation

Each day contains:

- Commands learned
- Short explanation of each command
- Hands-on exercises
- Practice notes
- Troubleshooting experience
- Daily logbook
- Evidence of completed exercises

Example daily structure:

```text
day-01/
├── commands.md
└── notes.txt

logbook/
└── day-01.md
```

## 🔀 Git Workflow

This repository uses a branch-based workflow to simulate a professional development workflow.

Each learning day should use a separate branch.

Example:

```bash
git switch main
git pull

git switch -c day-02-filesystem
```

After completing the laboratory:

```bash
git status
git add .
git commit -m "docs: add day 2 linux filesystem lab"
git push -u origin day-02-filesystem
```

Then create a Pull Request from:

```text
day-02-filesystem
        ↓
      main
```

After reviewing the changes, merge the Pull Request into `main`.

## 🌿 Branch Naming Convention

Branches should describe the purpose of the work.

Examples:

```text
day-01-linux-cli
day-02-filesystem
day-03-users-permissions
day-04-process-management
day-05-package-management
day-06-networking
day-07-troubleshooting
day-08-bash-scripting
```

For documentation changes:

```text
docs/improve-readme
docs/update-logbook
```

For fixes:

```text
fix/day-01-documentation
```

## 📝 Commit Convention

Commits should be short and descriptive.

Examples:

```text
docs: add day 1 linux cli lab
docs: update linux command reference
docs: add day 2 filesystem lab
fix: correct linux command documentation
```

## 🚀 Progress

| Status | Day | Topic |
|---|---|---|
| ✅ | Day 01 | Linux CLI Fundamentals |
| ⬜ | Day 02 | Linux Filesystem & File Operations |
| ⬜ | Day 03 | Users, Groups & Permissions |
| ⬜ | Day 04 | Processes & System Management |
| ⬜ | Day 05 | Package Management |
| ⬜ | Day 06 | Networking Fundamentals |
| ⬜ | Day 07 | Logs & Troubleshooting |
| ⬜ | Day 08 | Bash Scripting Fundamentals |
| ⬜ | Day 09 | Environment Variables & Shell |
| ⬜ | Day 10 | Linux Mini Project |

## 🧩 Skills Practiced

### Linux

- Linux CLI
- Filesystem navigation
- File and directory management
- File permissions
- Users and groups
- Process management
- Package management
- Networking
- Logs
- Troubleshooting

### Shell & Bash

- Bash
- Environment variables
- Pipes
- Redirection
- Command substitution
- Bash scripting

### DevOps Workflow

- Git
- GitHub
- Branching
- Commits
- Pull Requests
- Documentation
- Troubleshooting
- Infrastructure mindset

## 🎓 DevOps Learning Journey

This repository is the Linux foundation of my broader DevOps learning journey.

The long-term learning path will progress through:

```text
Linux
  ↓
Git & GitHub
  ↓
Bash
  ↓
Docker
  ↓
CI/CD
  ↓
Cloud
  ↓
Infrastructure as Code
  ↓
Terraform
  ↓
Ansible
  ↓
Kubernetes
  ↓
Monitoring & Observability
```

Each major technology will eventually have its own dedicated repository and practical projects.

## 🏗️ Future Projects

The Linux laboratory will be followed by dedicated repositories for other DevOps technologies.

Planned areas include:

```text
devops-linux-lab
        ↓
devops-docker-lab
        ↓
devops-cicd-lab
        ↓
devops-terraform-lab
        ↓
devops-ansible-lab
        ↓
devops-kubernetes-lab
        ↓
devops-monitoring-lab
```

Each repository will contain:

- Learning roadmap
- Daily hands-on exercises
- Mini projects
- Documentation
- Troubleshooting notes
- Git workflow
- Pull Requests
- Project evidence

## 📖 Learning Philosophy

The focus of this laboratory is not only memorizing commands.

The goal is to understand:

```text
What does the command do?
        ↓
Why is it used?
        ↓
How does it work?
        ↓
Can I use it in a real problem?
        ↓
Can I document it?
        ↓
Can I explain it to someone else?
```

Every exercise should produce a visible result that can be documented and reviewed.

## 📌 Current Status

**Current focus:** Linux Fundamentals

**Current environment:** WSL Ubuntu

**Current laboratory:** Day 01 — Linux CLI Fundamentals

**Current workflow:**

```text
Practice
   ↓
Document
   ↓
Commit
   ↓
Push
   ↓
Pull Request
   ↓
Review
   ↓
Merge
```

Built as part of my hands-on DevOps learning journey.
