# Git Commands

## Frequently Used Commands
### git clone https://github.com/markrobertdavid/git-demo.git
### git checkout release/specific-branch (Copy code from github branch)
### git checkout -b release/new-branch-name (Create new local branch)
### git add start.txt (Put files in git staging area)
### git commit -m "Adding start text file" (Put files for staging to the local repository)
### git pull origin main (Just to make sure that the repo is up-to-date)
### git push origin main
#### -> main refers to our default branch in the repository
#### -> Put changes on Github repository

## Configuration Commands
### git version
### git config --global user.email "markrobertdavid@gmail.com"
### git config --global user.name "Mark Robert"
### git config --global core.editor "notepad++.exe -multiInst -nosession"
### git config --global -e (This will run notepad++)
### git config --global --list

## Other Commands
### git commit -am "Shorthand for git add and git commit"
### git ls-files (List of all files that git is tracking)
### git reset HEAD filename.txt (This will remove the file from staging but the changes are still there)
### git checkout -- filename.txt (This will revert the file to the original state)
### git mv oldfilename.txt newfilename.txt (Command to rename file)
### git mv filename.txt foldername (Moving file up one level)
### git mv filename.txt .. (Moving file down one level)
### git rm filename.txt (Delete file that is being monitored by git)
### git log (Display git log history)
### git log -- filename.txt (Display commits that involves this file)
### git diff (Display the difference between the working and staging directory)
### git diff HEAD (Git will compare the working directory and the last commit in the stage directory)
### git diff --staged HEAD (Git will compare the staging directory and the last commit in the git repository)
### git diff -- filename.txt (Display difference on a specified file)
### git diff HEAD HEAD^ (Compare the last commit and the second to the last commit)
### git diff a123a3 dsf21a (Compare two specified commits IDs)
### git diff master origin/master (Compare local directory and Github master repository)

# CMD Commands
### mkdir folderName (Used to create a folder)
### mkdir -p level1/level2/level3/level4
### pwd (Display current directory)
### ls (List the files in the folder)
### ls -al (List all files including dot files and folders)
### rm -rf foldernameORfilename (Delete file or folder)
### echo "Test Git Quick Start demo" >> start.txt (Create a text file and write text inside)
### cat start.txt (Command to display the contents of that file)
### cp filename.txt copyfilename.txt (Copy command)
### exit (Close Git-bash)
### ~ (Shorthand for the users home directory)