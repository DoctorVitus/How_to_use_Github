## ❓ How to use GitHub
### 1. Git bash
```
    git config --global user.name "your_name"
    git config --global user.email "your_email"
    git config --list
```
    In details : [블로그 주소]

### 2. Code Upload
```
    git init
    git branch -m main
    git add "file_name" or git add .
    git status
    git commit -m "first commit"
    git remote add origin git@github.com:DoctorVitus/How-to-use-Github.git
    git remote -v
    git push origin main
```
    In details : [블로그 주소]
    
### 3. Update
```
    git add .
    git commit -m "second commit"
    git push origin main
```
    In details : [블로그 주소]
    
### Possible Errors
```
    Error : ! [rejected] master -> master (fetch first) error: failed to push some refs to
    Solution : git pull --rebase origin main
```

