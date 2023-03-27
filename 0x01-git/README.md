# Github common commands
## 1. Git clone
Git clone is a command for downloading existing source code from a remote repository (like Github, for example). In other words, Git clone basically makes an identical copy of the latest version of a project in a repository and saves it to your computer.
```git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-pre_course.git ```
## 2. Git branch
Branches are highly important in the git world. By using branches, several developers are able to work in parallel on the same project simultaneously. We can use the git branch command for creating, listing and deleting branches.
* Creating a new branch: ```git branch <branch-name>``` - This command will create a branch locally.
* Viewing branches: ```git branch``` or ```git branch --list ```
* Deleting a branch: ```git branch -d <branch-name>```
## 3. Git checkout
This is also one of the most used Git commands. To work in a branch, first you need to switch to it. We use git checkout mostly for switching from one branch to another. We can also use it for checking out files and commits.

```git checkout <name-of-your-branch>```
## 4. Git status
The Git status command gives us all the necessary information about the current branch. 

```git status```
We can gather information like:

* Whether the current branch is up to date
* Whether there is anything to commit, push or pull
* Whether there are files staged, unstaged or untracked
* Whether there are files created, modified or deleted

## 5. Git add
When we create, modify or delete a file, these changes will happen in our local and won't be included in the next commit (unless we change the configurations).

We need to use the git add command to include the changes of a file(s) into our next commit. 

To add a single file: ```git add <file>```

To add everything at once:```git add -A``` or ```git add .```
## 6. Git commit
This is maybe the most-used command of Git. Once we reach a certain point in development, we want to save our changes (maybe after a specific task or issue).

Git commit is like setting a checkpoint in the development process which you can go back to later if needed.

We also need to write a short message to explain what we have developed or changed in the source code.

```git commit -m "commit message"```
