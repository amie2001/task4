```markdown
# Task 4 - Version-Controlled DevOps Project with Git

## Objective:
Manage a DevOps project using Git best practices.

## Tools Used:
- Git
- GitHub
- EC2 (for command-line practice)

---

## Git Workflow Followed:

### 🔹 Repository Setup
```bash
git init
git remote add origin https://github.com/amie2001/task4.git
git branch -M main
git push -u origin main
```

### 🔹 Branching Strategy
```bash
git checkout -b dev
git push origin dev

git checkout -b feature/task-1
git push origin feature/task-1
```

### 🔹 Making Changes
```bash
nano feature.txt
git add feature.txt
git commit -m "Added feature.txt from feature branch"
git push origin feature/task-1
```

### 🔹 Pull Request Workflow
- Pull request created on GitHub from `feature/task-1` → `main`
- Merged via GitHub UI

### 🔹 Resolving Push Errors
```bash
git pull --rebase origin main
```

### 🔹 Git Ignore
```bash
nano .gitignore
git add .gitignore
git commit -m "Add .gitignore file"
git push origin main
```

### 🔹 Tagging
```bash
git tag v1.0 -m "First version of Task 4 project"
git push origin v1.0
```

---

## Branches:
- `main`: Stable production-ready code.
- `dev`: Integration branch.
- `feature/task-1`: Isolated feature development.

---

## Deliverables Completed:
- [x] GitHub Repo
- [x] Proper Branching
- [x] Pull Requests
- [x] README.md
- [x] .gitignore
- [x] Git Tag (`v1.0`)
- [x] Markdown documentation

---

## Author:
**R.L. Pavithra**

