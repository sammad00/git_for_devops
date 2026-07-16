# Git Commands Practice Guide

## 1. Create a Project
```bash
mkdir git_practice
cd git_practice
pwd
ls
```

---

## 2. Create and Edit Files
```bash
touch nibba.txt
touch nibbi.txt
touch niboo.txt

vim helo.txt
vim nibba.txt
vim nibbi.txt
vim branching.md

cat helo.txt
cat nibbi.txt
cat branching.md

ls
ls -a
ls -l helo.txt
```

---

## 3. Remove Files
```bash
rm -f helo.txt
rm nibbi.txt
```

---

## 4. Initialize Git Repository
```bash
git init
```

---

## 5. Configure Git
```bash
git config --global user.name "sammad00"
git config --global user.email "sammad77067@gmail.com"
```

---

## 6. Check Repository Status
```bash
git status
```

---

## 7. Stage Changes
```bash
git add .
git add nibba.txt
git add nibbi.txt
git add niboo.txt
git add branching.md
```

---

## 8. Unstage a File
```bash
git rm --cached nibbi.txt
```

---

## 9. Restore Deleted File
```bash
git restore nibbi.txt
```

---

## 10. Commit Changes
```bash
git commit -m "adding nibba and nibbi"

git commit -m "Add some new changes"

git commit -m "adding some items in nibba.txt file"

git commit -m "added niboo"

git commit -m "adding some features"

git commit -m "adding some links about git"

git commit -m "correction in words"

git commit -m "made some changes in Spells"
```

---

## 11. View Commit History
```bash
git log

git log --oneline
```

---

# Branching

## 12. View Branches
```bash
git branch
```

---

## 13. Create a New Branch
```bash
git checkout -b dev

git checkout -b staging
```

---

## 14. Switch Between Branches
```bash
git checkout main

git checkout master

git checkout dev

git checkout feature

git checkout staging
```

---

## 15. Merge Branches
```bash
git merge feature

git merge dev
```

---

# Remote Repository

## 16. Pull Latest Changes
```bash
git pull origin main

git pull origin staging
```

---

## 17. Push Changes
```bash
git push origin dev

git push origin main

git push origin staging

git push -u origin staging
```

---

# Linux Commands Used During Git Practice

## 18. List Files
```bash
ls

ls -a

ls -l
```

---

## 19. Change Directory
```bash
cd github/

cd git_for_devops/

cd .git

cd ..
```

---

## 20. Print Working Directory
```bash
pwd
```

---

## 21. View Command History
```bash
history
```

---

# Complete Git Workflow Example

```bash
mkdir git_practice
cd git_practice

git init

git config --global user.name "sammad00"
git config --global user.email "sammad77067@gmail.com"

touch nibba.txt
touch nibbi.txt

git add nibba.txt
git add nibbi.txt

git commit -m "Initial commit"

git checkout -b dev

touch niboo.txt
git add niboo.txt
git commit -m "Added niboo"

git checkout -b feature

vim branching.md
git add branching.md
git commit -m "Added branching documentation"

git checkout dev
git merge feature

git checkout -b staging
git merge dev

git checkout main
git merge dev

git push origin dev
git push origin staging
git push origin main

git pull origin main

git log --oneline
git status
git branch
```

---

# Git Commands Covered

- git init
- git config
- git status
- git add
- git rm --cached
- git restore
- git commit
- git log
- git log --oneline
- git branch
- git checkout
- git checkout -b
- git merge
- git push
- git push -u
- git pull
```

