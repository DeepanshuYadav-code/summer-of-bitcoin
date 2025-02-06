## Git Commands

### Basic
```bash
 git init
 git add .
 git commit -m "Comment"
 ```
Now suppose you want to create a new brach because you want to add new feature/code to the project. Then use git branches
```bash
git checkout -b <my-branch-name>
```
You can use the command **git branch** to check whether your branch was created.
- Every repository's firsst branch is named as **Master**
To push the changes in the new branch on GitHub
```bash
git push origin <your-branch-name>
```
- Then create a pull request
- Merge the pull request form github repo

Get changes back to your github repo (when working on the primary branch)
```bash
git pull origin master
```
Now use the command **git log** to view all the commits

### [GitHub Cheat Sheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf)

### [How to write a perfect PR](https://github.blog/developer-skills/github/how-to-write-the-perfect-pull-request/)