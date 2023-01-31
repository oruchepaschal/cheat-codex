# Git Codex

Git is a system that helps multiple people work on files together, tracking changes and coordinating work. It is mainly used for software development, but can be used for any set of files.

## Glossary
* **git**: An open source, distributed version-control system.
* **Branch**: A lightweight movable pointer to a commit.
* **Clone**: A local version of a repository, including all commits and branches.
* **Commit**: A Git object, a snapshot of your entire repository compressed into a SHA.
* **Fork**: A copy of a repository on GitHub owned by a different user.
* **HEAD**: Representing your current working directory, the HEAD pointer can be moved to different branches, tags, or commits when using git checkout.
* **Pull request**: A place to compare and discuss the differences introduced on a branch with reviews, comments, integrated tests, and more.
* **Remote**: A common repository on that all team member use to exchange their changes.
* **.gitgnore file**: Sometimes it may be a good idea to exclude files from being tracked with Git. This is typically done in a special file named `.gitignore`.
* **.Github**: xxx

## Basic Commands
Command | Description | Example(s)
------------ | ------------- | -------------
git add `file` | Snapshot the file in preparation for versioning | git add `index.rb`
git add -p | Select changes to add | git add -p
git blame `file` | Show who changed what & when in a file | git blame `file`
git clone `url` | Clone an entire repository from a remote location onto a local machine | git clone `https://github.com/promisepreston/example.git`
git commit -m `message` | Commit staged snapshots permanently in version history | git commit -m `initial commit`
git commit --amend | Modify the last commit’s message | git commit --amend
git init | Initialize the current directory as a git repository | git init
git init `directory` | Create an empty git repository in specified directory | git init `myapp`
git show `commit` | Output metadata and content changes of the specified commit | git show `4a0b8b5`
git status | List which files are staged, unstaged, and untracked | git status