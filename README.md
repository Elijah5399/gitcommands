# gitcommands

<h2>A repository to practice and save git commands</h2>

This is an additional edit.

1.  git clone [repository to be copied from (usually from github)] [destination (usually an empty file in the local computer)]
2.  git add [filenames]
    Stages the files for commit. Use git add . to stage all files in the current working repository.
3.  git commit
    Commits all staged files and changes
    Use git commit -m [message] to add a message to the commit
4.  git push
    Pushes committed changes to github.
    Use git push origin [branch-name] to push the branch and all committed
    changes to the remote.
5.  git branch [name]
    creates a new branch with the given name.
    Use git branch -d [branch name] to delete a branch.
    Use git branch -a to view all branches and current branch.
6.  git fetch
    fetches changes to the shared repository but does not merge with them
7.  git merge [branchname]
    Merges the current working branch with the specified branch.
8.  git pull
    Does a fetch and a merge. i.e. updates your files with all updates other people made.
9.  git checkout [branchname]
    Changes to the specified branch
10. git reset
    If you want to go back to a previous state, use git reset commit_SHA where
    commit_SHA is the commit id.
    Can also do git reset HEAD filename to remove a file from the staging area.
    This does not discard changes.

Common git collaboration workflow:
(1) Create your own branch on github and initialise it locally.
For this, create the branch on github, then do git pull. Now you can see the branches other people created locally, at the branch origin/branchname.
(2) Merge with other people's changes
For this, use git merge branchname, then manually resolve merge conflicts.
(3) Commit and push changes
USe git add ., git commit and git push to push the branch changes to github
(4) Submit a pull request on github
(5) If the changes are acceptable, accept the pull request.
This merges the changes onto main.
