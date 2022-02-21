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
### git config --global user.email "youremail@gmail.com"
### git config --global user.name "Mark Robert"
### git config --global core.editor "notepad++.exe -multiInst -nosession"
### git config --global -e (This will run notepad++)
### git config --global --list

## Other Commands
### git commit -am "Shorthand for git add and git commit"
### git ls-files (List of all files that git is tracking)
### git checkout -- filename.txt (This will revert the file to the original state)
### git mv oldfilename.txt newfilename.txt (Command to rename file)
### git mv filename.txt foldername (Moving file up one level)
### git mv filename.txt .. (Moving file down one level)
### git rm filename.txt (Delete file that is being monitored by git)
### git log (Display git log history)
### git log -- filename.txt (Display commits that involves this file)
### git branch (Display a list of all the branches)
### git branch -d branchnamehere (This will delete a specified branch)
### which git (Display the location of git)
### git commit --amend (This will allow you to update your commit message)
### git reflog (Show a log of everything we done)

## Git Diff Commands
### git diff (Display the difference between the working and staging directory)
### git diff HEAD (Git will compare the working directory and the last commit in the stage directory)
### git diff --staged HEAD (Git will compare the staging directory and the last commit in the git repository)
### git diff -- filename.txt (Display difference on a specified file)
### git diff HEAD HEAD^ (Compare the last commit and the second to the last commit)
### git diff a123a3 dsf21a (Compare two specified commits IDs)
### git diff master origin/master (Compare local directory and Github master repository)

## Git Stash Command
### git stash save "Stash name here"
### git stash list (This will display all the saved stashes)
### git stash show stash@{0} (Display the changes on stash index 0)
### git stash apply stash@{1} (Apply changes on stash index 1)
### git stash drop stash@{1} (Delete stash index 1)
### git stash clear (Delete all saved stash)
### git stash -u (Stash all files including the new files)
### git stash branch newbranchname
#### -> A new branch is created
#### -> Switch to the newly created branch
#### -> All stashed files will be applied
#### -> At the end the applied stash will be dropped

## Git Tag
### Lightweight Tags
#### git tag tagnamehere (Create a reference or alias to a commit)
#### git tag -list (List all the tags)
#### git show tagnamehere (Git will display the commit with that tag)
#### git tag --delete tagnamehere (This will delete the tag)

### Annotated Tags (Has additinal information)
#### git tag -a v-1.0 (Enter your own version)
#### git tag --list (Display all tags)
#### git log --oneline --graph --decorate --all
#### git show v-1.0 (Display details on specified tag)
#### git tag v-1.2 -m  "Tag message here"
#### git diff v-1.0 v-1.2 (Diplay the difference between two tags)
#### git tag -a v-0.9-beta 54ef98d (Add annotated tag on a specified commit)
#### git tag -a v-0.8-alpha -f 98ew45e (Moving tag to another commit by force)
#### git push origin v-0.9-beta (Pushing tag to Github)
#### git push origin master --tags (Push all tag to Github)
#### git push origin :v-0.8-alpha (Delete a specified tag)

## Git Reset Commands
### git reset HEAD filename.txt (This will remove the file from staging but the changes are still there)
### git reset HEAD^ (Backup one level)
### git reset HEAD^^ (Backup two level)
### git reset HEAD@{2}
### git reset 4b5e2da

# CMD Commands
### mkdir folderName (Used to create a folder)
### mkdir -p level1/level2/level3/level4
### pwd (Display current directory)
### ls (List the files in the folder)
### ls -al (List all files including dot files and folders)
### clear (Clear the command display)
### rm -rf foldernameORfilename (Delete file or folder)
### echo "Test Git Quick Start demo" >> start.txt (Create a text file and write text inside)
### cat start.txt (Command to display the contents of that file)
### cp filename.txt copyfilename.txt (Copy command)
### exit (Close Git-bash)
### ~ (Shorthand for the users home directory)