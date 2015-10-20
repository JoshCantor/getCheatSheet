## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Shows differences between the commits, commit and working tree. These can be structured in multiple ways depending on what you are trying to see the differences. Examples: Changes between the working tree and the index or a tree, changes between the index and a tree, changes between two trees, changes between two blob objects, or changes between two files on disk.

#### Repo History
`$ git log` - __Fill Me Out__

`$ git log --oneline --decorate --color --graph --all` - __Fill Me Out__

`$ git log -p [filename]` __Fill Me Out__

#### Stage files to commit
`$ git add <filename>` - Adds file contents to the staging area based on the file name. If no filename is specified, 

`$ git add -A` - Adds updates to the entire working tree - downstream. This command can also have a <pathspec> which updates both the index and the specified <pathspec>.

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - Provides the commit message on the command line. Let's the admin and other users know any specific information about the commit. 

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Fill Me Out__

