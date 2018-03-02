# Remove Git Tags Not in Remote
From: https://stackoverflow.com/a/27254532
```bash
# git 2.1.3
git fetch --prune origin "+refs/tags/*:refs/tags/*"

# git 2.18.0
git fetch --prune --prune-tags origin 
```