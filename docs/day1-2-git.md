# Git Learning Documentation – Day 1 & Day 2 🚀

## 👤 Learner
**Name:** Rohith Amalan J

---

## 📘 Day 1 – Git Fundamentals

### 🔹 What is Version Control?
Version control is a system that tracks changes to files over time. It allows developers to collaborate efficiently and revert to previous versions when needed.

---

### 🔹 Why Git?
- Tracks source code history
- Supports team collaboration
- Enables offline work
- Industry standard version control system

---

### 🔹 What is Git?
Git is a **Distributed Version Control System (DVCS)** where every developer has a complete copy of the repository and its history.

---

### 🔹 Centralized vs Distributed Version Control

| Centralized VCS | Distributed VCS |
|---------------|----------------|
| Single central server | Multiple local repositories |
| Requires internet | Works offline |
| Single point of failure | Fault tolerant |

---

### 🔹 Git Configuration Levels
Git supports three configuration levels:

- **System level** – applies to all users
- **Global level** – applies to a single user
- **Local level** – applies to a specific repository

---

### 🔹 Commands Practiced (Day 1)
```bash
git --version
git init
git status
git add README.md
git commit -m "Initial commit"
git log --oneline
```

---

## 📘 Day 2 – Modifying, Staging & Undoing Changes

### 🔹 Git File Lifecycle
```
Untracked → Modified → Staged → Committed
```

---

### 🔹 Modifying Files
Changes were made to `README.md` and verified using:
```bash
git diff
```

---

### 🔹 Staging & Committing Changes
```bash
git add README.md
git commit -m "Updated README with Day 2 learning"
```

---

### 🔹 Undoing Changes
```bash
git restore README.md
git restore --staged README.md
git reset --soft HEAD~1
```

---

## 🧠 Key Learnings
- `git status` shows file state
- `git diff` shows exact changes
- Staging is required before committing
- Git allows safe recovery from mistakes

---

## ✅ Outcome
Successfully practiced Git fundamentals, file tracking, commits, and undo operations using hands-on exercises.
