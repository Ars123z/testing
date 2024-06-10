git branch
======================
1. git branch <branchname> -> creates new branch
2. git checkout <branchname> -> head moves to the branch <branchname>
3. git commit at different branches create diversions
4. git merge <branchname> (from the branch you wanna merge into)
5. git branch -d <branchname>(to delete branch after merging)
6. git branch to show all the branches available
7. git checkout -b <branchname> (to create a branch and checkout at the same time)
8. git branch -v -> to see the last commit on each branch
9. git branch (--merged or --no-merged) -> to see the list of merged branch with the current branch
10. git branch --move <branchname> <newbranchname> -> to change a branchname (git push --set-upstream origin main, git push origin --delete master) -> to push the corrected branchname to remote


git log <branchname> to show the commit history upto that branch
git log --all to show all the commit history

<!-- However, before you do that, note that if your working directory or staging area has uncommitted changes that conflict with the branch you’re checking out, Git won’t let you switch branches. It’s best to have a clean working state when you switch branches. -->

<!-- This is add in the iss53 branch -->
<!-- this comment is on the hotfix branch -->