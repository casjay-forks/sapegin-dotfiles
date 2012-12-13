# Git Awesomeness

## Aliases

### Shorthands

* **git a** → git add

* **git ua** → git reset HEAD

* **git b** → git branch

* **git c** → git commit

* **git ca** → git commit -a

* **git cm** → git commit -m

* **git cam** → git commit -am

* **git co** → git checkout

* **git d** → git diff --color-words

* **git s** → git status -sb

### git l

Simple one-line-per-commit log.

### git ll

Log with list of changed files for each commit.

###	git ignore <file mask>

Add new item to `.gitignore`.

### git this

Initialize Git repo in current folder and commit all files.

### git append

Add all staged files to previous commit.

### git undo

Undo last commit withould loosing any changes.

### git conflicts

List of files with unresolved conflicts.

### gr

Jump to root folder of Git repo.

### git-github [repo]

Setup syncronization of current Git repo with GitHub repo of the same name

### git-bitbucket [repo]

Setup syncronization of current Git repo with Bitbucket repo of the same name

### git-fork <original-author>

Add remote upstream.

### git-upstream [branch]

Sync branch with upstream.


## [git-friendly](https://github.com/jamiew/git-friendly)

### pull

Stash any local changes, pull from remote using rebase, updates submodules, pop your stash, then run `bundle install` and/or `npm install` if necessary.

### push

Push your changes to the remote + copy a sexy diff URL like http://github.com/jamiew/git-friendly/compare/e96033…5daed4 to your clipboard (works on Mac and Linux).

### branch [name]

Switch branches or create new local branch if it doesn’t exist. Intelligently sets up remote branch tracking so you can just type `git pull` and not always `git pull origin newbranch`. If no argument specified will list all local and remote branches.

### merge [name]

Merge the specified branch into the current branch. Rebases first if the branch is local-only.


## [git-extras](https://github.com/visionmedia/git-extras)

See `git extras --help` or [documentation](https://github.com/visionmedia/git-extras/blob/master/Readme.md) for all available commands.


## [hub](https://github.com/defunkt/hub)

See `hub help` or [documentation](http://defunkt.io/hub/hub.1.html) for all available commands.