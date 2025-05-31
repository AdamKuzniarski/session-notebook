GIT Commands

git status - Check status of your repository untracked/modified/staged/commited

git init project1 - Initialize Git on the curren folder

git add [file1.txt] - Select which changes will go into next commit
git add -A - Select all files to next commit
git . - Sellect all files to next commit
git restore --staged [file1.txt] - Unstage a file

git commit -m 'My first commit' - Add commit to your file/files
git commit -a -m 'My second commit' - Add commit to your files (skip staging), do not work with untracked files.
git commit - Open Vim and you can write Multi-line commit messages

git reset --soft HEAD~1 - Undo your last commit and keep your changes staged

git stash - Stash your changes, if you need to quick change your branch without commiting
git stash clear - Delete all your stashes at once


git branch [branch-name] - Create a new branch
git branch - To see all branches in your repository
git checkout [branch name] - Switch between branches
git branch -d [branch-name] - Delete a branch


git log - see commit history. To quit from 'log' use q button
git log --since='1 week ago' - Show only commits from the las week

git help [command] - See help for a command
git [command] -h - See a quick summary of options. to QUIT help pages use q button


