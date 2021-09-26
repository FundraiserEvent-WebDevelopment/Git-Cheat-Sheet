# Git Cheat Sheet and Example Workflow

## Introduction

Git is the most commonly used version control system among developers. It allows developers to easily revert changes in their code, as well as work with other developers without constantly stepping on each others toes.

It does this through a system of local and remote repositories. The primary repository, or remote, will be hosted on a server, in this case GitHub. Each developer will be able to clone their own copy of the repository, allowing them to work without overwriting the work of other developers.

## Getting Started

### Installation

If you are running Windows, you will have to install git from the official git website, [git-scm.com](https://git-scm.com/).

In the event you are running Linux, the chances are very high that the software came pre-installed when setting up your distro. If it did not, you can easily install it by using your package manager, such as `apt`, `pacman`, or `rpm`.

Many Mac machines also have Git pre-installed.

### Basic Commands

While Git has a huge number of commands which allow advanced users to do some incredible things with the software, a majority of developers will only need to use a few. They are as follows

 - **clone** - Takes the URL of a remote repository and copies it to your local machine.
 - **add** - Takes the name of any files on your local machine and adds them to your local repository (Must be followed by a commit command to save)
 - **commit** - Creates a commit, permenantly storing state of repository, allowing rollbacks or a remote push
 - **push** - Pushes current local repo to remote repo
 - **pull** - Pulls any new changes in the remote repo down into the local repo.
 - **branch** - Creates a new branch in current repo.
 - **merge** - Takes a branch and merges it with your current branch.