# Build a Version-Controlled DevOps Project with Git

## 🎯 Objective
Manage a DevOps project using Git best practices.

---

## 🛠 Tools Used
- **Git**
- **GitHub**

---

## 📦 Deliverables
- Project repository with:
  - Proper commits
  - Branching strategy
  - Pull requests & merges
  - `README.md` documentation
  - `.gitignore` file
  - Git tags

---

## 🔑 Steps Followed

### 1. Initialize Repository
```bash
git init
git remote add origin <repo-url>
git push -u origin main
```

### 2. Branching Strategy
- **main** → Stable production-ready branch  
- **dev** → Integration branch  
- **feature/** → For new feature development  

```bash
git checkout -b dev
git checkout -b feature/login
```

### 3. Pull Requests
- Pushed feature branches to GitHub
- Opened Pull Requests (PRs) to merge into `dev`
- Once tested, merged `dev` into `main` via PR

### 4. Added README.md
This file explains the entire project.

### 5. Used .gitignore
Ignored files like:
```
*.log
*.tmp
.env
__pycache__/
```

### 6. Added Git Tags
```bash
git tag -a v1.0 -m "First stable release"
git push origin v1.0
```

### 7. Documentation in Markdown
All tasks were documented step by step using markdown.

---

## ✅ Outcome
- Learned **Git version control workflows**
- Understood **branching, PRs, and tagging**
- Created a **well-documented project repo**

---

## ❓ Interview Questions & Answers

1. **What is Git?**  
   Git is a distributed version control system that tracks changes in source code and enables collaboration.

2. **What is the difference between merge and rebase?**  
   - *Merge*: Combines changes into a new commit, preserving history.  
   - *Rebase*: Moves commits on top of another branch, creating a linear history.

3. **What is a pull request?**  
   A way to propose changes in a branch and request merging into another branch (commonly dev → main).

4. **How do you resolve merge conflicts?**  
   - Identify conflicts with `git status`  
   - Edit conflicting files  
   - Mark as resolved: `git add <file>`  
   - Commit the merge

5. **What are Git tags?**  
   Tags are references that point to specific commits, usually for marking releases.

6. **What is Git workflow?**  
   A set of guidelines on how teams use branches, commits, and pull requests (e.g., GitFlow, trunk-based).

7. **Explain git stash.**  
   Temporarily saves uncommitted changes without committing them, allowing you to work on something else.

8. **What is the use of .gitignore?**  
   To exclude files/folders (logs, credentials, build artifacts) from being tracked in Git.

