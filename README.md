Practical:  To perform version control on websites/software using GIT.
1. Create an new folder and add some file in the folder
2. Perform all the below commands in CMD of the folder you have created 
3. Check if git is downloaded by command : git --version
4. git config --global user.name "add your name"
5. git config --global user.email "add github email addresss"
6. git init // You just created your first Git Repository!
7. git status // 
8. git add "add your file name with extension" // This command updates the index using the current content found in the
working tree, to prepare the content staged for the next commit. It typically
adds the current content of existing path as a whole, but with some options it
can also be used to add content with only part of the changes made to the
working tree files applied, or remove paths that do not exist in the working tree
anymore.
9. git commit -m "write any message like (file added successfully)" // Since we have finished our work, we are ready move from stage to commit for
our repo. Adding commits keep track of our progress and changes as we work.
Git considers each commit change point or "save point". It is a point in the
project you can go back to if you find a bug, or want to make a change. When
we commit, we should always include a message. By adding clear messages to
each commit, it is easy for yourself (and others) to see what has changed and
when.
10. git status -–short // And check the status of our repository. But this time, we will use the --short
option to see the changes in a more compact way:
11. git log // To view the history of commits for a repository, you can use the log command:
12. create new branch command : git branch "branchName" // We are working in our local repository, and we do not want to disturb or
possibly wreck the main project. So, we create a new branch:
13. Check if master branch and your branch is present or not command: git branch
14. git checkout "master" // Checkout is the command used to check out a branch. Moving us from the
current branch, to the one specified at the end of the command:
15. git merge "your branch name" // Command is used to merge different branches into the main branch.
16. git branch -d "your branch name" // Command is used to delete a branch.
