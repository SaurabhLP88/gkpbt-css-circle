# Git Workflow Practice Project

This project is a hands-on exercise to understand **forking**, **pull requests**, and working with **upstream repositories**. It demonstrates how to contribute to open-source projects using GitHub and Git commands.

This mini project demonstrates a standard GitHub contribution workflow (forks, branches, pull requests) and a quick front-end exercise: **creating a perfect circle using a `<div>`**.

---

## 🧭 Goals
- Get familiar with **forks** and **pull requests**
- Use git commands to manage an **upstream** repository
- Practice secure auth with a **Personal Access Token (PAT)**
- Make a small UI change: **CSS circle using a div**

---

## ✅ Prerequisites
- Git installed
- GitHub account
- (Recommended) SSH keys or a **Personal Access Token (PAT)** for HTTPS pushes

---

## 1) Workflow: Fork → Clone → Branch → Commit → Push → PR

### 1. Create a Personal Access Token (PAT)
- GitHub → **Settings** → **Developer settings** → **Fine-grained tokens** (or **Classic**)
- Give repo scopes (e.g., `repo`) → Generate and copy the token
- Use it instead of password when pushing over HTTPS

### 2. Fork the Repository
- On GitHub, open the original repo → click **Fork**

### 3. Clone Your Fork
```bash
git clone https://github.com/SaurabhLP88/gkpbt-css-circle.git
cd gkpbt-css-circle
