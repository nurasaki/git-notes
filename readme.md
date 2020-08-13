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

Add changes
- `git add .`  (to update what will be committed)
- `git commit -a -m "some changes notes"` (add + commit, -a add; -m message)
- `git push` (push changes to master branch)
- `git push origin --force`

Download changes
- `git pull`

**Resolve conflicts force overwrite**
- `$ git fetch --all` 1) First fetch all changes:
- `$ git reset --hard origin/master` (2) Then reset the master:
- `$ git pull` (3) Pull/update:

Control commands
- `git log`
- `git status`


## Upload changes
```
$ git push origin master
```




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
