## Git Hidden Folder

There is a hidden folder calls `.git` which tells you that the project is in a repo

Create a git repo is a new project, create a folder then initialize that repo using `git init`

```
mkdir /Users/mac/Desktop/new-project
cd /Users/mac/Desktop/new-project
git init
touch Readme.md
open Readme.md
git status
git add Readme.md
#Make changes to Readme.md
git commit - a -m "Add and message for Readme.md file"
```

## Cloning

We can clone 3 ways: HTTPS, SSH, Githubn CLI

Using Github Codesopaces we will create a temperatory directory in our workspace

```sh
mkdir /Users/mac/Desktop/Projects 2024
cd /Users/mac/Desktop/Projects 2024
```

## HTTPS

```sh
git clone git@github.com:fiona-spencer/git-commands.git
```

## Commits

## Branches

## Remotes

## Stashing

## Merging

Use . to stage all possible files that will be included in the commit

```
git add Readme.md
git add .
```

## Reset

Reset allows you to move staged changes to be unstaged.
Useful to revert all files to not be commited

```
git add .
git reset
```

> git reset will revert a get add .