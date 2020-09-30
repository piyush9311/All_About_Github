# All_About_Github 

About Github
GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project.

BASIC COMMANDS

1.git init will create a new local GIT repository. 
The following Git command will create a repository in the current directory:
git init

2.git clone is used to copy a repository. If the repository lies on a remote server, use:
git clone username@host:/path/to/repository

Conversely, run the following basic command to copy a local repository:
git clone /path/to/repository

3.git add is used to add files to the staging area. For example, the basic Git following command will index the temp.txt file:
git add <temp.txt>

4.git commit will create a snapshot of the changes and save it to the git directory.
git commit –m “Message to go with the commit here”

5.git status displays the list of changed files together with the files that are yet to be staged or committed.
git status

6.git push is used to send local commits to the master branch of the remote repository. Here’s the basic code structure:
git push origin <master>

7.git checkout creates branches and helps you to navigate between them. For example, the following basic command creates a new branch and automatically switches you to it:
command git checkout -b <branch-name>

To switch from one branch to another, simply use:
git checkout <branch-name>

8.git remote lets you view all remote repositories. The following command will list all connections along with their URLs:
git remote –v

To connect the local repository to a remote server, use the command below:
git remote add origin <host-or-remoteURL>

Meanwhile, the following command will delete a connection to a specified remote repository:
git remote rm <name-of-the-repository>

9.git branch will list, create, or delete branches. For instance, if you want to list all the branches present in the repository, the command should look like this:
git branch

If you want to delete a branch, use:
git branch –d <branch-name>

10.git pull merges all the changes present in the remote repository to the local working directory.
git pull

11.git merge is used to merge a branch into the active one.
git merge <branch-name>

12.git diff lists down conflicts. In order to view conflicts against the base file, use
git diff --base <file-name>

The following basic command is used to view the conflicts between branches before merging them:
git diff <source-branch> <target-branch>

To list down all the present conflicts, use:
git diff

13.To delete a repository created using init, use:
rmdir.git
