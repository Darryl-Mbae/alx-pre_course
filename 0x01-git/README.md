# Github common commands
## 1. Git clone
Git clone is a command for downloading existing source code from a remote repository (like Github, for example). In other words, Git clone basically makes an identical copy of the latest version of a project in a repository and saves it to your computer.
```root@896cf839cf9a:/# git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-pre_course.git ```
## 2. Git branch
Branches are highly important in the git world. By using branches, several developers are able to work in parallel on the same project simultaneously. We can use the git branch command for creating, listing and deleting branches.
* Creating a new branch: ```git branch <branch-name>``` - This command will create a branch locally.
* Viewing branches: ```git branch``` or ```git branch --list ```
* Deleting a branch: ```git branch -d <branch-name>```
