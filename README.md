## ❓ How to use GitHub
### 1. Git bash
Set User's name
```
    git config --global user.name "your_name"
```
Set User's E-mail (Use your github email!)
```
    git config --global user.email "your_email"
```
Check your name & e-mail address
```
    git config --list
```

### 2. Code Upload
Initialize your git
```
    git init
```
Change from master to main branch
```
    git branch -M main
```
Add your code file
```
    git add "file_name" or git add .
```
Check status (Optional)
```
    git status
```
Make a history
```
    git commit -m "first commit"
```
Connect github repository to my local project
```
    git remote add origin git@github.com:DoctorVitus/How-to-use-Github.git
```
Check if it is well connected (Optional)
```
    git remote -v
```
Upload your code file to Github
```
    git push origin main
```
In details
```
    https://ymechanics.tistory.com/entry/Github-%EA%B9%83%ED%97%88%EB%B8%8C-%EA%B8%B0%EB%B3%B8-%ED%99%9C%EC%9A%A9%EB%B2%95-%EC%A0%95%EB%A6%AC
```
    
### 3. Update
Update your code file
```
    git add "file_name" or git add .
```
Make a additional history
```
    git commit -m "second commit"
```
Update your code file to Github
```
    git push origin main
```
In details
```
    [블로그 주소]
```
 
### 4. Possible Errors
```
    Error : ! [rejected] master -> master (fetch first) error: failed to push some refs to
    Solution : git pull --rebase origin main
```

