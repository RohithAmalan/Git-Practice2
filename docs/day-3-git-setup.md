# Day 3 – GitHub Setup & Push 🚀

## 🎯 Objective
Connect a local Git repository to GitHub and push commits to a remote repository.

---

## 🔹 What is GitHub?
GitHub is a remote code hosting platform used to store, manage, and collaborate on Git repositories.

---

## 🔹 Steps Performed

### 1. Created a GitHub Repository
- Repository name: git-practice
- Visibility: Public
- No README, .gitignore, or license added initially

---

### 2. Added Remote Origin
```bash
git remote add origin <repository-url>
git remote -v
```

---

### 3. Pushed Code to GitHub
```bash
git push -u origin main
```

---

## 🧠 Key Learnings
- `origin` refers to the remote GitHub repository
- `main` is the default branch
- `git push` uploads local commits to GitHub

---

## ❗ Common Issues & Fixes
- Authentication issues resolved using GitHub Personal Access Token
- Remote errors fixed by verifying `origin`

---

## ✅ Outcome
Local repository successfully connected and pushed to GitHub.
