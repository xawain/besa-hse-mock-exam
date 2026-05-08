# Local Version Control

This folder is tracked with local Git so changes can be reviewed and rolled back before a remote repository is added.

## Common Commands

```bash
git status
git diff
git add .
git commit -m "Describe the change"
git log --oneline
```

## Later, When You Add A Remote

```bash
git remote add origin <your-repo-url>
git branch -M main
git push -u origin main
```

