# BASIC IMPORTANT NOTES FOR GITHUB IN CMD & VSCODE

### 1. **Cloning a Repository**
```bash
git clone <repository-url>
```
Example:
```bash
git clone https://github.com/BarbaraNeanake/PAW16-Basic-CRUD-API.git
```

### 2. **Checking Current Branch**
```bash
git branch
```

### 3. **Creating a New Branch**
```bash
git checkout -b <branch-name>
```
Example:
```bash
git checkout -b feature-branch
```

### 4. **Switching to Another Branch**
```bash
git checkout <branch-name>
```
Example:
```bash
git checkout main
```

### 5. **Adding Files to Staging Area**
```bash
git add .
```
Or, to add specific files:
```bash
git add <file-name>
```
Example:
```bash
git add index.js
```

### 6. **Committing Changes**
```bash
git commit -m "Your commit message"
```
Example:
```bash
git commit -m "Update route for books"
```

### 7. **Pushing Changes to Remote Repository**
```bash
git push origin <branch-name>
```
Example:
```bash
git push origin main
```

### 8. **Pulling Changes from Remote Repository**
```bash
git pull origin <branch-name>
```
Example:
```bash
git pull origin main
```

### 9. **Merging a Branch**
First, switch to the branch you want to merge into (usually `main`):
```bash
git checkout main
```
Then, merge your branch:
```bash
git merge <branch-name>
```
Example:
```bash
git merge feature-branch
```

### 10. **Check Status of Current Changes**
```bash
git status
```

### 11. **Undo Changes (Reset a File)**
To discard changes in a specific file:
```bash
git checkout -- <file-name>
```
Example:
```bash
git checkout -- index.js

### 12. **Stashing Changes**
To temporarily store changes without committing:
```bash
git stash
```

To apply stashed changes later:
```bash
git stash apply
```

### 13. **Pull and Merge Automatically**
This will automatically fetch and merge changes from the remote:
```bash
git pull origin <branch-name> --rebase
```
---

With these commands, you’ll be able to do most basic Git operations directly in VSCode.
