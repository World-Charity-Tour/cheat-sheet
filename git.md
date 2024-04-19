# Create Feature Branch and Push

```
git checkout staging
git fetch origin
git reset --hard origin/staging
git checkout -b <FEATURE> 
git add .
git commit "<MSG>"
git push -u origin <FEATURE> 
```