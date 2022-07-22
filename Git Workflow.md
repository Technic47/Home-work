# Git Workfow

## Git

### Basic comands

* **git init**

Tells Git to create repository in selected folder.

* **git status**

Shows status of repository. Reviews modifired files.

* **git add /filename/**

Adds file for commitment. 

 >*git add '.\Git Workflow.md'*

* **git add .**

Adds all files in active folder for commitement.

>*git add .*

* **git commit**

>*git commit -m "text"*

Creates a commitment for all changes of files with comment in "text".

>*git commit -am "text"*

Creates a commitment for all changes __without *git add .*__ of files with comment in "text".

### Branches

* **git branch**

Shows all branches and highlight active one.

* __git branch *branchname*__

Creates new branch.

* __git checkout *branchname*__

Change branch to other.

* __git checkout *hash*__

Goes to commitement with selected *hash*.

* __git checkout -b *branchname*__

Create new branch and make it active.

* __git branch -d *branchname*__

Delete branch. You may write several branchnames and all of them will be deleted.

* __git branch -M *new_branchname*__

Rename active branch.

* __git merge *branchname*__

Adds branch with *branchname* to active branch.

### Support commands

* **clear**

Clears terminal log.

* **q**

Use Q to exit to general terminal comands.

* **git diff**

Shows difference beetwin last commitment add actual file.

>*git diff "hesh1" "hesh2"*

Shows difference in 2 selected commitements.

* **git log**

Shows log of last commitments in active branch.

* **git log --graph**

Shows all commitments with tree structure.

* **git log --oneline**

Shows all commitments with simplified tree structure.

* **git reflog**

Shows all logs.

* __git tag *text*__

Adds tag to last commitment.

* **git stash**

Hide last changes.

* **git stash apply**

Apply hidden changes.

* **git *command* --help**

>*git commit --help*

Shows info about any command.

## GitHub

### Basic comands

* **git clone https://.......**

Clones repository from selected adress in github.

* __cd *text*__

Change directory to folder *text*.

* **git pull**

Download commitments from github repository.

* **git push**

Sands commitments to githus repository.

### Workflow

To import somebody`s github repository you need to:

>1. Create folder and chose it. Do not use git init command.

>2. Use git clone *adress* command.

To create your repository on github it you need to:

>1. Create new repository on site.
>>[GitHub new](https://github.com/new  "New repository creation")
>2.  Use guidelines on GitHus to create a new or uploaв your existing repository.
>3.  Use commands shown on GitHub in terminal.

