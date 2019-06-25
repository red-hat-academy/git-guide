# Part 1
> Welcome to part 1, the part after part 0 and before part 2. 

## Explaining The Initial Setup
So the initial setup may have been a little vague but here is a small explanation of exactly what you were doing there. The rest of the modules will have explanations along with the instructions.

### Forking
When you fork a project you are creating your own copy of a project to modify in any way you want. Forking allows you to change or add to a project in any way. You can submit a pull request to merge any changes or additions with the upstream project that you forked. This is how you can contribute to a project on GitHub that you do not have write access to.

### Cloning
Cloning a project is also making a copy of the repository but it is used for downloading a project along with it's history to your local machine. This will create a local project directory and will allow you to edit it and track changes all locally. Later you can push those changes back to the remote repository that you cloned provided you have write access.

## Instructions for Part 1
### Branching
Branches are used for diverging from the main line of development. Say that you have a Developer who wants to add a new feature into your project. The Developer wants to change a bunch of things for the feature but doesn't want to affect the main development line. That Developer would create a branch for that new feature and would build it there. When the developer finishes, the feature can be merged into the main branch and released. This allows for a single project to be separated into multiple lines of development.
### Checking out a Branch
When you checkout a branch you are just switching to that development line in your project. to checkout a branch use this command

`git checkout <branch name>`

When this command is executed you will switch to the branch specified.

To create a new branch the same command is used with the `-b` option:

`git checkout -b <new branch name>`

Continue to the next step by checking out an existing branch called "partTwo" from the remote repository (origin) then the instructions for part two will then show up.

`git checkout -b partTwo origin/partTwo`
