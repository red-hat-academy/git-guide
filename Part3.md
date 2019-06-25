# Part 3
> The shiny new part 3.

Welcome to part 3. Here we'll take a look at another type of merging, pull requests.
### Pull Request
Pull requests allow you to tell others about changes that you've pushed to a branch in a repository. It is essentially a merge with the opportunity for a peer review.

## Instructions
> Part 4 has been finished and is ready to be merged with this branch!

### Creating a Pull Request
Create and merge a pull request to merge the changes from the partFour branch into the partTwo branch. Then use git pull to update your local repository.

First, navigate to your repository in GitHub.

1. Click **New Pull Request**
2. Select the base as partTwo and the compare as partFour

When you review what will be changed you will see that a new section is to be added called `Part4.md`. You can add a comment if you want. Generally this section will be used to determine the purpose of the request when reviewing it.

4. Click **Create Pull Request**

A pull request has now been created to merge changes from the branch partFour into partTwo.

### Accepting a Pull Request
Next you need to accept the pull request that you just created to merge the changes. You could require the pull request to be approved by those who have write access to the repository as part of the review process. To learn more about merging pull requests check out the official [GitHub documentation](https://help.github.com/en/articles/merging-a-pull-request).

1. To merge a pull request click **Pull requests** under the repository name.
2. From here you will get a list of pull request to your repository, click the **Merge pull request** button to merge the request.
3. Go back to your local repository and run the `git pull` command to update your local repository with the changes from the merge.

You Should now see Part 4 in the instructions directory!