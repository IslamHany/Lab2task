# Lab 2 solution
![github logo](githublogo.png)
### Create a new project on your local machine then push it to your remote repo

```sh
$git init
$git remote add origin https://github.com/IslamHany/Lab2task.git
$git push origin master
```

# create two branches (dev and test) then create two files in dev branch and push this changes to remote repo

```sh
$git branch test
$git checkout -b dev
$touch file1 file2
$git add .
$git commit -m "add file1, file2"
$git push origin dev
```
# merge this changes on main branch and then push it to your remote main branch
```sh
$git checkout master
$git merge dev
$git push origin master
```

# remove branches locally
```sh
$git branch -d dev test
```

# remove branches remotely
```sh
$git push origin --delete dev
```

# create an annoted tag with tagname v1.4
```sh
$git tag v1.4
```

# pushit to remote server
```sh
$git push origin v1.4
```

# tell me how to list tags locally
```sh
$git tag
```

# deletetag locally
```sh
$git tag -d v1.4
```

# delete tag remotely
```sh
$git push --delete origin v1.4
```

# my github profile
[profile](https://github.com/IslamHany)