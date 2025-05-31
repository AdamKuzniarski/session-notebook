GIT Commands

git status - Check status of your repository untracked/modified/staged/commited

git init project1 - Initialize Git on the curren folder

git add [file1.txt] - Select which changes will go into next commit
git add -A - Select all files to next commit
git . - Sellect all files to next commit
git restore --staged [file1.txt] - Unstage a file

git commit -m 'My first commit' - adds commit to your file/files
git commit -a -m 'My second commit' - adds commit to your files (skip staging), do not work with untracked files.
git commit - open vim and you can write Multi-line commit messages

git reset --soft HEAD~1 undo your last commit and keep your changes staged



git log - see commit history. To quit from 'log' press q button

git switch [branch name]- switch between branches
