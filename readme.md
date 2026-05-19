# 🚀 Complete GitHub Course (বাংলা)
# Beginner → Advanced Professional Guide

> সম্পূর্ণ GitHub শেখার বাংলা Documentation  
> Beginner থেকে Professional Workflow পর্যন্ত

---

# 📚 Full Topic Navigation

1. [GitHub Introduction](#-module-1--github-introduction)
2. [Git vs GitHub](#-git-vs-github)
3. [Repository](#-module-2--repository)
4. [Public vs Private Repository](#-public-vs-private-repository)
5. [README.md](#-readmemd)
6. [.gitignore](#-gitignore)
7. [GitHub Account Setup](#-github-account-setup)
8. [Create Repository](#-create-repository)
9. [Local Project Setup](#-local-project-setup)
10. [GitHub Remote Connection](#-github-remote-connection)
11. [Push / Pull / Clone](#-module-5--push--pull--clone)
12. [Branch Workflow](#-module-6--branch-workflow)
13. [Merge & Conflict](#-merge--conflict)
14. [Pull Request (PR)](#-module-7--pull-request-pr)
15. [Fork & Open Source](#-module-8--fork--open-source)
16. [Issues & Collaboration](#-module-9--issues--collaboration)
17. [SSH vs HTTPS](#-module-10--ssh-vs-https)
18. [Professional Workflow](#-module-11--professional-workflow)
19. [Best Practices](#-module-12--best-practices)
20. [Important Commands Cheat Sheet](#-important-commands-cheat-sheet)
21. [Final Learning Outcome](#-final-learning-outcome)

---

# 📘 Module 1 — GitHub Introduction

## 📌 GitHub কী?

GitHub হলো Cloud-based Git hosting platform।

এটি ব্যবহার করা হয়:
- Code Hosting
- Collaboration
- Portfolio
- Open Source Contribution
- Backup

---

# 📌 Git vs GitHub

| Git | GitHub |
|---|---|
| Local software | Online platform |
| Version control | Collaboration |
| Offline কাজ করে | Internet লাগে |

---

# 📘 Module 2 — Repository

## 📌 Repository কী?

Repository হলো Project container যেখানে:
- Source code
- History
- Branches
- README
- Issues

থাকে।

---

# 📌 Public vs Private Repository

## Public
- সবাই দেখতে পারবে
- Portfolio এর জন্য ভালো

## Private
- শুধু আপনি বা Team দেখতে পারবে
- Client Project এর জন্য ভালো

---

# 📘 README.md

README হলো Project documentation file।

Example:

```md
# Flutter Ecommerce App

Modern ecommerce app using Flutter
```

---

# 📘 .gitignore

যে file Git track করবে না।

Example:

```gitignore
build/
.env
node_modules/
```

---

# 📘 GitHub Account Setup

Website:
https://github.com

---

# 📘 Create Repository

GitHub Dashboard থেকে:
- New Repository
- Repository Name
- Public / Private
- Create Repository

---

# 📘 Local Project Setup

```bash
mkdir github-course
cd github-course
git init
```

---

# 📘 GitHub Remote Connection

```bash
git remote add origin https://github.com/user/repo.git
```

Check Remote:

```bash
git remote -v
```

---

# 📘 Module 5 — Push / Pull / Clone

## Push

```bash
git push -u origin main
```

## Pull

```bash
git pull origin main
```

## Clone

```bash
git clone https://github.com/user/repo.git
```

---

# 📘 Module 6 — Branch Workflow

## Branch Create

```bash
git switch -c feature-login
```

## Merge

```bash
git merge feature-login
```

---

# 📘 Merge & Conflict

Conflict Example:

```text
<<<<<<< HEAD
My Code
=======
Team Code
>>>>>>>
```

Fix করার পর:

```bash
git add .
git commit
```

---

# 📘 Module 7 — Pull Request (PR)

PR হলো Code Review Request।

Workflow:

```text
Create Branch
    ↓
Code
    ↓
Commit
    ↓
Push
    ↓
Create PR
    ↓
Review
    ↓
Merge
```

---

# 📘 Module 8 — Fork & Open Source

Fork মানে অন্যের repository নিজের account এ copy করা।

Open Source Contribution এ ব্যবহার হয়।

---

# 📘 Module 9 — Issues & Collaboration

Issues ব্যবহার করা হয়:
- Bug Tracking
- Feature Request
- Discussion

---

# 📘 Module 10 — SSH vs HTTPS

## HTTPS

```text
https://github.com/user/repo.git
```

## SSH

```text
git@github.com:user/repo.git
```

---

# 📘 Module 11 — Professional Workflow

```text
Clone Repo
    ↓
Create Feature Branch
    ↓
Code
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

---

# 📘 Module 12 — Best Practices

✅ Small commits করুন  
✅ Proper commit message ব্যবহার করুন  
✅ Feature branch ব্যবহার করুন  
✅ Pull before push করুন  
✅ Secrets upload করবেন না  

---

# 📘 Important Commands Cheat Sheet

```bash
git init
git status
git add .
git commit -m "message"

git branch
git switch -c branch-name
git merge branch-name

git push
git pull
git clone URL

git stash
git stash pop

git reset --hard HEAD~1
git revert COMMIT_ID
```

---

# 🎯 Final Learning Outcome

এই Course শেষে আপনি পারবেন:

✅ GitHub professionally ব্যবহার করতে  
✅ Pull Request করতে  
✅ Team collaboration করতে  
✅ Open source contribution শুরু করতে  
✅ Professional workflow maintain করতে  

---

# ❤️ Happy Coding

Made for Beginner Developers 🚀
