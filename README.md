# gitcommands

A repository to practice and save git commands

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
9.  git checkout [branchname]]
    Changes to the specified branch

Common git collaboration workflow:
(1) Fetch and merge changes from the remote
(2) Create a branch to work on a new project feature
(3) Develop the feature on a branch and commit the work
(4) Fetch and merge from the remote again (in case new commits were made)
(5) Push branch up to the remote for review
