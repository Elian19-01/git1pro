# The git / github with examples:

## initial configuration

  ```shell
  git config --global user.name "Elian Vega"
  ```
  ```shell
  git config --global user.email 2009142@upy.edu.mx
  ```

## Starting a project from zero or clone
  
  to clone a existing project
  ```shell
  git clone Elian19-01@host:/path/to/repository
  ```
  
## basic workflow commands to stage and commit
  
  ```shell
  git add Test.txt

  git commit -m "testcommit"
  ```
## to push to a remote repository

 It will uploand the commits to a remote repository
 ```shell 
 git push -u origin main
  ```


## Branches

 to create a branch
  ```shell
  git checkout -b testbranch
  ``` 
 to delete a branch
  ```shell
  git checkout -d secondbranch
  ``` 
 to combine a branch with the current branch
  ```shell
  git merge testbranch
  ```

## git flow

To execute workflow on git flow.
  ```shell
  git flow init
  ```

To reate a function branch
  ```shell
  git flow feature start feature_branch    
  ```
## References
 
  ```shell
 [texto del enlace](url ejemplo https://www.hostinger.es/tutoriales/comandos-de-git)
```
