# Git cli commands
Git basic commands.


#### Initial Configuration
*For windows:* 
>  git config --global core.autocrlf true

*For linux/macOS:*
>  git config --global core.autcrlf input


#### Creating and managing a repository
Initialize repo:
>  git init
  
Adding first files to repo:
>  git add file1.txt file2.java\
>  git commit -m "commit description"
  
Stage some changes to a file
>  git add file1\
>  git commit -m "updated repo with new changes"
  
Delete a file from the repo
>  *on the system delete the file*\
>  git add file1\
>  git commit -m "removed file1"
>  
Faster way to commit changes
>  git commit -am "Adding **ALL** files to stage area and commiting"

Staging area status
>  git status

List staging area files
>  git ls-files

#### 
