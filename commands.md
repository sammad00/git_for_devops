# Git Practice Commands

## 1. Create and Navigate to Project
```bash
mkdir git_practice
cd git_practice
pwd
ls
```

## 2. Create and Manage Files
```bash
vim helo.txt
cat helo.txt
ls -l helo.txt
touch nibba.txt
touch nibbi.txt
touch niboo.txt
rm -f helo.txt
rm nibbi.txt
```

## 3. Initialize Git Repository
```bash
git init
ls -a
cd .git
ls
cd ..
```

## 4. Check Repository Status
```bash
git status
```

## 5. Stage Files
```bash
git add nibba.txt
git add nibbi.txt
git add niboo.txt
```

## 6. Unstage a File
```bash
git rm --cached nibbi.txt
```

## 7. Configure Git User
```bash
git config --global user.name "sammad00"
git config --global user.email "sammad77067@gmail.com"
```

## 8. Edit Files
```bash
vim nibba.txt
vim nibbi.txt
cat nibbi.txt
```

## 9. Commit Changes
```bash
git commit -m "adding nibba and nibbi"
git commit -m "Add some new changes"
git commit -m "adding some items in nibba.txt file"
git commit -m "added niboo"
```

## 10. Restore Deleted File
```bash
git restore nibbi.txt
```

## 11. View Commit History
```bash
git log
git log --oneline
```

## 12. Branch Management
```bash
git branch
git checkout -b dev
git checkout master
git checkout dev
```

## 13. List Files
```bash
ls
```

## 14. View Command History
```bash
history
```

---

# Git Workflow Summary

```bash
mkdir git_practice
cd git_practice

git init

touch nibba.txt
touch nibbi.txt

git add nibba.txt
git add nibbi.txt

git commit -m "adding nibba and nibbi"

git checkout -b dev

touch niboo.txt
git add niboo.txt
git commit -m "added niboo"

git checkout master

git log --oneline
git branch
git status
```
