
## Log ##
Show log as a graph git 
```
log --graph --oneline --all
```

## Working with Remote ##
Stop tracking remote branch : 
 ```
 git branch --unset-upstream
 git branch -D -r origin/<remote branch name>
 ```  
 
 ## Change the commit message ##
 Not Pusehd + Last Commit : 
 ```
 git commit --amend
 ```
 
 Pushed + Last Commit : 
 ```
 git commit --amend 
 git push origin master --force 
 ```
 ( if someone alredy checked the commit, it will be out of sync)
 
 Not Last Commit : Use Interactive rebase 
 
 ## Alias ##
 Create an Alias 
 ``` 
 git config --global alias.ci "commit -v"
 ``` 
