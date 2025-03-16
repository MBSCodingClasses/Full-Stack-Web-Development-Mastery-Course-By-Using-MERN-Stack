```markdown
# Git and GitHub Cheat Sheet

This is a simple cheat sheet for Git and GitHub commands, perfect for quick reference.

---

## Git Setup

### Configure Git with Your Name and Email
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

---

## Repository Setup

### Initialize a New Git Repository
```bash
git init
```

### Link Your Remote GitHub Repository
```bash
git remote add origin https://github.com/username/repository.git
```

---

## Track Changes

### Stage Files for Commit
```bash
git add filename
```
Or stage all files:
```bash
git add .
```

### Commit Changes
```bash
git commit -m "Your commit message"
```

### View Commit History
```bash
git log
```

---

## Branching

### Create a New Branch
```bash
git branch branch_name
```

### Switch to a Different Branch
```bash
git checkout branch_name
```

### Merge Branches
```bash
git merge branch_name
```

### View All Branches
```bash
git branch
```

---

## Remote GitHub Commands

### Pull Latest Changes from GitHub
```bash
git pull origin main
```

### Push Changes to GitHub
```bash
git push origin branch_name
```

---

## Undo Changes

### Unstage Changes
```bash
git reset HEAD filename
```

### Undo All Changes in a File
```bash
git checkout -- filename
```

---

## Git Status and Diff

### Check the Status of Your Repository
```bash
git status
```

### See What Changes Have Been Made
```bash
git diff
```

---

## GitHub Specific Commands

### Clone a GitHub Repository
```bash
git clone https://github.com/username/repository.git
```

### Push to GitHub
```bash
git push -u origin main
```

---

## Simple Git Workflow Example

1. **Initialize a Git Repository**
   ```bash
   git init
   ```

2. **Stage Files**
   ```bash
   git add .
   ```

3. **Commit Changes**
   ```bash
   git commit -m "First commit"
   ```

4. **Push to GitHub**
   ```bash
   git push -u origin main
   ```

---

## Quick Glossary

- `git add`: Stages changes for the next commit.
- `git commit`: Saves changes to the local repository.
- `git push`: Uploads local changes to a remote repository.
- `git pull`: Downloads changes from the remote repository to local.
- `git branch`: Manages branches in your repository.
- `git merge`: Merges one branch into another.

---

This cheat sheet covers the most commonly used Git and GitHub commands to help streamline your development process.
```
