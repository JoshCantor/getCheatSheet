## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - __Fill Me Out__

#### Repo History
`$ git log` - Keeps a record of what has been committed, with the bottom being the oldest and the top being the latest of the commits.

`$ git log --oneline --decorate --color --graph --all` - The -oneline takes the message of your commits, through a history log. The decorate changes the font styles and color of the HEAD, master, and origin/master. The --graph shows a linear time line (vertically) so that it would be easier for the reader to see the history log.

`$ git log -p [filename]` Shows the last commit, and it's message.

#### Stage files to commit
`$ git add <filename>` - __Fill Me Out__

`$ git add -A` - __Fill Me Out__

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Fill Me Out__