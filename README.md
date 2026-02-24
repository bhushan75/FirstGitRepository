# FirstGitRepository

This is my First Git Repository, 
<br>
and .md = mark down
<br>
Setup Git with VS Code
<br>
1) Download VS Code
2) https://git-scm.com/download/win
3) ~ -- meaning of this tilt symbol mean we are in Root Directory/Folder.

<br>
   open GitBash App
<br>
   1) commands: - ls - all the files in directory, pwd - current directory, clear - to clear the content

<br>
Git Commands: - 
<br>
1) git config --global user.name "username" -- to setup username on git 
2) git config --global user.email "useremail" -- to setup an email on git
3) git config -- list -- to get the list of values that we set above
4) git clone <some Link> -- to clone all the files from the folder to VS Code from Github or our local system (laptop/desktop
5) git status  -- displays the state of code 
6) cd -- Change Directory -- to change our folder in command prompt


There are 4 types of status
1) untracked : - new files created and not commited
2) modified : - updated the file and not commited
3) staged : - 
4) unmodified: - unchanged/ no changes required.

Staged means adding file , not commit

there are 2 steps: - add --> commit == Staged --> Commit

1) add - add changes /staged changes
 git add <fileName> - to add specific files
 git add . - to add all files

2) commit - commit the changes
git commit -m "someMessage"

3) Push - deploy changes to server / github
git push origin main



