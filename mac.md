## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
Git is an open source distributed version control system

2. What is the difference between Git and GitHub? 
GitHub is a for-profit, cloud-based hosting service that lets you manage Git repositories. Git is a software and GitHub is a service.

3. Why do we create a branch? 
Creating a new branch isolates your work from team members. This allows many developers to work on one project at the same time without interfering with each others' code.

4. What is the purpose of a Pull Request? 
A pull request is how you tell others about changes you've pushed so that they can be reviewed and approved prior to merging them into the main branch.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main. 
git branch Name-of-branch (In this case, it would be git branch main)

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch - downloads all history from the remote tracking branches. Allows you to see changes made to a repo without actually merging the changes.
git merge - joins two or more development histories together. Any changes from the named commits become incorporated into the current branch.
git pull - updates your current local working branch with all new commits from the corresponding remote branch on GitHub (combination of git fetch and git merge)
7. What is a merge conflict?
A merge conflict is an event that takes place when Git is unable to automatically resolve differences in code between two commits due to competing changes. They usually occur when two people have changed the same lines in a file or if one developer deleted a file while another was modifying it.
8. How do you resolve a merge conflict?
To resolve a merge conflict, you must manually edit the conflicted file to select the changes that you want to keep in the final merge. git log --merge will produce the list of commits that are causing the conflict. Find the conflicting files and make necessary changes, commit changes, then create a new commit and a new merge.
If the conflict is caused by competing line changes, such as people making different changes to the same line of the same file on different branches, you can resolve on GitHub using the conflict editor.
For all other types of merge conflicts, you must resolve the conflict in a local clone of the repo and push the change to GitHub.
