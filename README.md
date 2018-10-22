# git_cheat_sheet
List of useful commands and resources for better a better git life
Please submit any ofyour own tips

## [How to Rename and local and remote branch](https://multiplestates.wordpress.com/2015/02/05/rename-a-local-and-remote-branch-in-git/) 
### Rename your local branch.
* If you are on the branch you want to rename:
    * git branch -m new-name
* If you are on a different branch:
  * git branch -m old-name new-name
### Delete the old-name remote branch and push the new-name local branch.
* git push origin :old-name new-name
### Reset the upstream branch for the new-name local branch.
* Switch to the branch
* git push origin -u new-name
