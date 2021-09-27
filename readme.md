## make more change from github website

## create a new repository on the command line
```echo "# Wine-Quality-is-BAD" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/subha996/Wine-Quality-is-BAD.git
git push -u origin main
```

## push an existing repository from the command line
```git remote add origin https://github.com/subha996/Wine-Quality-is-BAD.git
git branch -M main
git push -u origin main
```

## also use to push code from local to github website
```bash
git push -u origin master
```


# Finalized Version Here...

### to initialize git
```
git init
```

### Adding all folder and files to git local cache
``` 
git add .

```

### Commiting all the files to local git cache, it is telling git that you are ready to push the code to remote server (github.com or github website)
```
git commit -m "commit message"
```

### Adding your remote repository link. Create this manually from gihub website or from terminal

``` 
git remote add origin https://github.com/subha996/repository_name.git
```

### Pusing code and files or Sending code and file to remote server or gthub website
```
git push -u origin master
```

### Now you are done, refresh your repository to see the changes 😋😋

## For pulling the file and folder from github
``` git pull origin master```
