## ❓ How to use GitHub
### 1. Git bash
Set User's name
```
    git config --global user.name "your_name"
```
Set User's E-mail (Use your gothub email!)
```
    git config --global user.email "your_email"
```
Check your name & e-mail address
```
    git config --list
```

### 2. Code Upload
```
Initialize
    git init
Set default branch
    git branch -M main
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

