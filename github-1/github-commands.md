# Git commands

`git status` - displays the state of the working directory and the staging area

`git add .` - The git add . command is used in Git to stage all changes in your working directory for the next commit. It includes:

- Modified files (files you edited)

- New files (files you created)

- Deleted files (files you removed)

`git commit -m"<text>"` -  git commit -m “commit message”. A shortcut command that immediately creates a commit with a passed commit message.

`git push origin <name of the branch>` - The git push command is used to upload local repository content to a remote repository.

`git pull` - used to fetch and download content from a remote repository and immediately update the local repository to match that content

`git checkout <name of the branch>` - lets you navigate between the branches created by git branch
After your pull request has been approved we use this command "git checkout <name of the branch>" in gitbash to change branches, we are gonna choose main to stay up to date and we are gonna use git pull command from main branch and after we are gonna get back to our "working branch" which is "development" in this case. 