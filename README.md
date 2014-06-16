adilapapaya.github.io
=====================

Useful git guides:
- [Git cheatsheet](https://github.com/github/training-materials/blob/master/downloads/github-git-cheat-sheet.pdf?raw=true)
- [rogerdudler.github.io/git-guide/](http://rogerdudler.github.io/git-guide/)

## Branching
[rogerdudler.github.io/git-guide/](http://rogerdudler.github.io/git-guide/)

Branches are used to develop features isolated from each other. The master branch is the "default" branch when you create a repository. Use other branches for development and merge them back to the master branch upon completion.


create a new branch named "feature_x" and switch to it using

```git checkout -b feature_x```

Switch back to master with 
```git checkout master```
and delete the branch again with
```git branch -d feature_x```
a branch is not available to others unless you push the branch to your remote repository:
```git push origin <branch>```
