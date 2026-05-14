# 📘 Git & GitHub Basic Class Notes

### Beginner Class Documentation (বাংলা)

👨‍🏫 **Prepared By:** Goutom Roy
💻 Flutter Mobile App Developer

⏱ **ক্লাস সময়:** ৩০ মিনিট
🎯 **লক্ষ্য:** Git এর একদম basic workflow বুঝা এবং প্রথম commit করা

---

# 🚀 আজকের ক্লাসে যা শিখবো

✅ Git কী
✅ GitHub কী
✅ Version Control System
✅ Git Install Check
✅ Repository তৈরি
✅ File Track করা
✅ Commit করা
✅ Git History দেখা

---

# 📌 Git কী?

Git হলো একটি **Version Control System (VCS)**।

এটি ব্যবহার করা হয়:

* Code এর history রাখার জন্য
* আগের version এ ফিরে যাওয়ার জন্য
* Team এ কাজ করার জন্য
* Project safely manage করার জন্য

---

# 📌 Real Example

ধরুন আপনি একটি app বানাচ্ছেন।

আজ:

* Login Page তৈরি করলেন

আগামীকাল ভুল করে সব delete করে ফেললেন।

Git থাকলে:

✔ আগের version এ ফিরে যেতে পারবেন
✔ কোন change কখন হয়েছে দেখতে পারবেন

---

# 📌 Git vs GitHub

| Git                | GitHub            |
| ------------------ | ----------------- |
| Local software     | Online platform   |
| Computer এ কাজ করে | Cloud এ code রাখে |
| Version control    | Collaboration     |

---

# 📌 Git Workflow

```bash
Create File
   ↓
git add
   ↓
git commit
   ↓
History Saved
```

---

# 📌 Step 1 — Git Install Check

টার্মিনালে লিখুন:

```bash
git --version
```

👉 যদি version দেখায় তাহলে Git install আছে।

### Example

```bash
git version 2.45.1
```

---

# 📌 Step 2 — Git Configuration

Git কে আপনার নাম ও email জানাতে হবে।

## 🔹 Name সেট করুন

```bash
git config --global user.name "Your Name"
```

## 🔹 Email সেট করুন

```bash
git config --global user.email "you@gmail.com"
```

## 🔹 সব Config দেখুন

```bash
git config --list
```

---

# 📌 Step 3 — Project Folder Create

```bash
mkdir git-basic-demo
```

👉 নতুন folder তৈরি হবে।

---

# 📌 Step 4 — Folder এ প্রবেশ

```bash
cd git-basic-demo
```

---

# 📌 Step 5 — Git Initialize

```bash
git init
```

👉 এটি folder কে Git repository বানাবে।

---

# 📌 Git Repository কী?

Repository হলো:

👉 Git tracked project folder

---

# 📌 Step 6 — File Create

## Windows

```bash
echo Hello Git > app.txt
```

## Mac/Linux

```bash
touch app.txt
```

---

# 📌 Step 7 — Git Status

```bash
git status
```

👉 Git কোন file change হয়েছে দেখাবে।

### Example

```bash
Untracked files:
app.txt
```

---

# 📌 Git Status Meaning

| Status    | Meaning                |
| --------- | ---------------------- |
| Untracked | Git এখনো track করছে না |
| Modified  | File change হয়েছে      |
| Staged    | Commit এর জন্য ready   |

---

# 📌 Step 8 — Git Add

```bash
git add .
```

👉 সব file staging area তে যাবে।

---

# 📌 Staging Area কী?

এটি commit এর আগে temporary area।

```bash
Working Directory
      ↓
Staging Area
      ↓
Commit
```

---

# 📌 Step 9 — Commit

```bash
git commit -m "First commit"
```

---

# 📌 Commit কী?

Commit হলো:

👉 Project snapshot save করা

---

# 📌 Step 10 — Commit History দেখুন

```bash
git log
```

👉 সব commit history দেখাবে।

---

# 📌 Short History

```bash
git log --oneline
```

### Example

```bash
a45f2d1 First commit
```

---

# 📌 দ্বিতীয় Commit Example

File edit করুন:

```bash
echo New Feature >> app.txt
```

তারপর:

```bash
git add .
git commit -m "Added new feature"
```

---

# 📌 Final Workflow

```bash
Create File
   ↓
git status
   ↓
git add .
   ↓
git commit
   ↓
git log
```

---

# 🧪 Class Practice Task

## টাস্ক ১

✔ Folder তৈরি করুন
✔ Git init করুন

---

## টাস্ক ২

✔ app.txt তৈরি করুন
✔ Commit করুন

---

## টাস্ক ৩

✔ আবার file modify করুন
✔ দ্বিতীয় commit করুন

---

# 📌 Important Commands Cheat Sheet

```bash
git --version

git config --global user.name "Your Name"

git config --global user.email "you@gmail.com"

git init

git status

git add .

git commit -m "message"

git log

git log --oneline
```

---

# 🎯 আজকের ক্লাস শেষে আপনি পারবেন

✅ Git initialize করতে
✅ File track করতে
✅ Commit করতে
✅ History দেখতে
✅ Basic Git workflow বুঝতে

---

# 📚 Homework

১. নতুন project তৈরি করুন
২. ৩টি commit করুন
৩. git log দেখুন
৪. Different commit message ব্যবহার করুন

### Example

```bash
Initial project setup

Added login page

Fixed button issue
```

---

# 👨‍🏫 Instructor

**Goutom Roy**
Flutter Mobile App Developer
