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
 ```shell 
 git push -u origin main
  ```

## Branches

 to create
  ```shell
  git checkout -b testbranch
  ``` 
 to delete
  ```shell
  git checkout -d secondbranch
  ``` 
 to combine
  ```shell
  git merge testbranch
  ```

## git flow

  ```shell
  git flow init
  ```

  ```shell
  git flow feature start feature_branch    
  ```
