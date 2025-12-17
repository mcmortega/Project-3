Create Readme.md


- Clone repo to local copy
```sh
git status
git pull origin
git checkout -b \<branch name>\
#Modify local files
git add .
git commit -m "<put comments>"
git push \<Remote URL\> \<branch name\> \(git push origin main\)
```


- Pull repo to local copy
```sh
git checkout main/master
git pull \<remote name\> \<branch\> \(git pull origin main/master\)
git checkout -b <new branch name>
#Modify files
git add .
git commit -m "<put comments>"
git push \<Remote URL\> \<branch name\> \(git push origin main\)
```