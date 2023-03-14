# .gitignore

When sharing your code with others, there are often files or parts of your project, you do not want to share.

Examples

* log files
* temporary files
* hidden files
* personal files etc.

Git can specify which files or parts of your project should be ignored by Git using a .gitignore file.

Git will not track files and folders specified in .gitignore. However, the .gitignore file itself IS tracked by Git.

## To create a .gitignore file, go to the root of your local Git, and create it:

Example
```touch .gitignore```
Now open the file using a text editor.

We are just going to add two simple rules:

* Ignore any files with the .log extension
* Ignore everything in any directory named temp

```
# ignore ALL .log files
*.log

# ignore ALL files in ANY directory named temp
temp/
```
