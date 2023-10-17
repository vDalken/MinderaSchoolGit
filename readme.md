# Repositorio
 A repository or more commonly known as repo is a tool used by programmers in order to apply changes to a project.
 It's one of the most important tools in any programmers arsenal, as it allows f
or a large team to add changes to a project without compromising the initial fil
e. Since it allows to create multiple points in a project development, any bug b
ug that appears or any mistake a developer makes, that person can easily go back
 to a version where it didn't happen. 
 There's a lot of companies that have cloud repos, making it even a more powerfu
ll instrument, because if anything happens to our machine, our files will be in
the cloud, making it easy to resume the project.
# Branch
 When we talk about branches, we have to know that there's the main one, the start of the project and then, we can
make different versions of the main branch. That allows the developers to write code without affecting the main branch
and creating problems. This way, the project is organized in different versions, versions that we can then merge with
the main branch and make permanent changes. 
# Commit
# Push
## The git push command is used to upload LOCAL repository content to a REMOTEe repository. Pushing is how you transfer commits from your local repository to a remote repo.
# Pull
## The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows.
# Diff
# Remote
The fact that GitHub's repositories are saved remotely, this means that the code can be access from anywhere with an internet connection by the developer.
This has numerous advantages some of them being: The security of always having the code saved in a cloud, making it unlikely that total data loss happens; the ease of accessibility means it's more versatile than just having the files saved locally; the fact that it's remote also facilitates collaboration between developers, which makes it so that physical access to the machine where the repo is being stored isn't necessary for any sort of changes.

# Local
# Clone
# Checkout
In Git terms, a "checkout" is the act of switching between different versions of a target entity. The git checkout command operates upon three distinct entities: files, commits, and branches. You can use git checkout on the command line to create a new branch, change your current working branch to a different branch, or even to switch to a different version of a file from a different branch with git checkout [branchname] [path to file]. The "checkout" action updates all or part of the working tree with a tree object or blob from the object database, and updates the index and HEAD if the whole working tree is pointing to a new branch.
# Merge
In a pull request, you propose that changes you've made on a head branch should be merged into a base branch. By default, any pull request can be merged at any time, unless the head branch is in conflict with the base branch. However, there may be restrictions on when you can merge a pull request into a specific branch. For example, you may only be able to merge a pull request into the default branch if required status checks are passing. Repository administrators can add constraints like this to branches using branch protection rules or repository rulesets.
# Conflict
When two or more people change the same file in different branches. The 
conflict symbolizes that two or more changes have been made to the same 
file and git doesn't know which of the changes to keep.
# Pull Request
Pull Request is like a notification. 
Basically, PR is a mechanism which the programmer signals that he has finished developing a feature.
And expect an analysis of the code.