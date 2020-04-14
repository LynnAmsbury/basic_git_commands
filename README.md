# Basic Git Commands

git init: initializes a folder with git. ONLY TYPE THIS WITHIN THE DIRECTORY YOU WANT GIT TO TRACK.

`rm -rf .git`: removes git initialization

`git status`: lists what has been done with the directory

`git add`: tells git to start tracking a file/directory

`git commit`: “captures” any changes since the last commit

`git commit -m “Message”`: allows you to leave a commit message describing the changes

* Adding `-a`: to the end = “all changes”

`git commit -am "A message”`: shortens the add and commit process as long as all files are being tracked

`git clone`: clones (copies) a repo from the internet onto your local machine

`git remote`: allows you to see the names of each remote repository available

`git remote add origin [your-copied-remote-repository-URL]`: connects a local repository to a remote repository

`git push`: allows you to send code to a remote repo

* Adding `-u` sets “upstream” branch

`git fetch`: updates your remote tracking branch to be in sync, or up-to-date, with the remote branch

`git add [file-name]`: adds ALL the changes in a file

`git add`: adds all the changes in all the files in the current directory

`git add images/.`: adds all the files in the `images` subdirectory

`git add -p`: `git add partial` (or patch): you to stage parts of a changed file instead of the entire file. Git will guide us to each "chunk" of changed content and confirm with us whether to stage or not to stage the "chunk" of change.

`git config --global core.editor "atom --wait”`: to configure Git to use a specific editor - in this case atom

`git push -u origin [new-branch-name]`: to push a new branch that does not yet exist on the remote repository

`git log`: outputs all commits made in a repository

`git diff`: shows us the differences between previous commits and current work, or between different branches, or anything else we need to track changes between

`git reset`: upstages changes
`git reset --soft HEAD~1`: undoes the most recent commit
`git reset --soft HEAD~3`: undoes the last 3 commits

`git checkout .`: clears changes from a working branch back to the last committed state (or the beginning)

`git checkout index.html`: clears changes to a single file back to the last commit (in this case `index.html`)
