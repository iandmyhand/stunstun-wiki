
**Configurations**
```
git config --global --list
git config --global user.name {username} 
git config --global user.email {email}
git config --global color.ui “auto”
``` 

**Basic**
```
git --version
git init
git add .
git commit -m "commit message"
git status
git diff
git mv {filename} {new-filename}
git checkout -- {filename}
```

**Branch & Tag**
```
git branch
git branch {branch-B} {branch-A}
git branch {new-branch}
git branch -d {branch}
git branch -m {branch} {new-branch}
```
**Remote**
```
git clone {address}
git fetch
git pull
git push
git remote add {name}
git remote
git remote show {name}
git remote rm {name}
```

## References
- https://blog.outsider.ne.kr/572

