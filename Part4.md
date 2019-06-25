# Part 4
> The Home Stretch

## Git Lifecycle
When using a git repository changes in that repository will follow a lifecycle.

 File Status	| Description 
--------------|-------------
 Untracked		| Files not in the repository or [ignored](https://git-scm.com/docs/gitignore)
 Unmodified		| A file that has not changed in the repo
 Modified			| A file that has changed in the repo
 Staged				| When a change is added to the list of changes that will be committed
 Committed		| The repository is updated with all of the staged changes returning everything that was staged to an unmodified state

These are two of the most common commands needed during the git file lifecycle.
Command		| Description
----------|-------------
git add		| adds a file to the list of staged changes
git commit| saves staged changes to the repository
git push	| will update remote repository with changes from local
git pull	| will update local repository with changes from remote

## Instructions
> Answer these questions. After that push those changes to the remote repository.

1. On GitHub, a copy of someone else's project that allows you to change it however you want without affecting the original work is called a ______.
2. ______ is a git command used to make a local copy of a remote repository.
3. A line of development that diverges from the main line so developers can continue work without messing with the main line is called a ______.
4. Combine all of the changes from two branches in a ______.
5. If you want your changes to a repository to become part of another that you don't have write access to then you can submit a ______.
6. When you are done making changes to a repository you need to ______ and then ______ those changes to the repository database.

After you have answered these questions type `git add *` to stage all of the changes in the repository.

Next type `git commit -m 'answered questions'`. The `-m` flag allows you to specify a short message to identify what changes were made in this commit.

Next use `git push` to update the remote repository with the changes you committed.


## After all of that your done!
I hope you've learned something about git in this tutorial. If you notice any mistakes in these exercises be sure to submit a pull request so they can be fixed :)