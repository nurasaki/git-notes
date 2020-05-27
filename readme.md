# Git basic commands

### Configuració inicial

```
$ git init 
$ git add filename (afegeix files a "index)
$ git commit -m 'nom commit'
$ git remote add origin https://github.com/nurasaki/git-notes.git
$ git push -u origin master
```


### Add changes

```
git commit -a -m "Added some changes"

# Option B
git add file1 file2
git commit -m "Added some changes"
```

- `-m` flag stands for message
- `-a` flag stands for "add" ()


### Altres
```
$ git status
$ git branch
$ git checkout nom_branca
$ git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
```

## URLs externes

- https://rogerdudler.github.io/git-guide/  
- https://www.git-tower.com/learn/git/commands/git-commit

Working Dir -> [add] Index (Stage) -> [commit] HEAD
