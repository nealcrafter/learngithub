65555A pull request is a proposal to merge a set of changes from one branch into another. In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase. Pull requests display the differences, or diffs, between the content in the source branch and the content in the target branch.
55
Note: When working with pull requests, keep the following in mind:
add note2

    If you're working in the shared repository model, we recommend that you use a topic branch for your pull request. While you can send pull requests from any branch or commit, with a topic branch you can push follow-up commits if you need to update your proposed changes.
    Be very very careful when force pushing commits to a pull request. Force pushing changes the repository history and can corrupt your pull request. If other collaborators branch the project before a force push, the force push may overwrite commits that collaborators based their work on.


After initializing a pull request, you'll see a review page that shows a high-level overview of the changes between your branch (the compare branch) and the repository's base branch. You can add a summary of the proposed changes, review the changes made by commits, add labels, milestones, and assignees, and @mention individual contributors or teams. For more information, see "Creating a pull request."
Once you've created a pull request, you can push commits from your topic branch to add them to your existing pull request. These commits will appear in chronological order within your pull request and the changes will be visible in the "Files changed" tab.
paste test
Other contributors can review your proposed changes, add review comments, contribute to the pull request discussion, and even add commits to the pull request. By default, in public repositories, any user can submit reviews that approve or request changes to a pull request. Organization owners and repository admins can limit who is able to give approving pull request reviews or request changes. For more information, see "Managing pull request reviews in your organization" and "Managing pull request reviews in your repository."
