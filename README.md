## Cheat Sheet
### Cairo is not supreme


Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Compares the changes between commits.

#### Repo History
`$ git log` - Shows commit logs.

`$ git log --oneline --decorate --color --graph --all` - - (Options) Shows colored changes, draws a graph, pretends as if all the refs in refs/ are listed on the command line as <commit>.

`$ git log -p [filename]` Shows commit of specific file.

#### Stage files to commit
`$ git add <filename>` - adds a specific filename to commit

`$ git add -A` - adds all files to commit

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - commits the file to be ready to be pushed with a message on what the file is about.

#### Branching
Branching as I understand it. You have a file in git and want to work on it. You create a branch with git branch. This creates a separate time line, that you can then make changes. When finished use merge to merge the branch with the master branch.

`$ git branch <branch name>` - __create a new branch__ with branch name is whatever you want.

`$ git branch` - __Lists all of the branches in the repository__

`$ git checkout <branch name>` - __Git checkout is a way for you to move from one branch to another.__

#### Merging

`$ git merge <branch name>` - __Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.__