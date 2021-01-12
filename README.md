## Git Intro Session BPHC

#### What is Git?
Git is a distributed version-control system for tracking changes in any set of files, originally designed for coordinating work among programmers cooperating on source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

#### Installing Git
Install git by visiting [https://git-scm.com/downloads](https://git-scm.com/downloads) and install the appropriate binary for your OS.

#### Common Git Commands
1. `git init` to create a new repository in a directory
2. `git add` to track files for changes
3. `git commit` commits those changes permanently in version control history
4. `git push` to push your work to a remote Git host
5. `git log` to see commit history
6. `git remote` to see what remotes is your repo connected to
7. `git branch` to create a new branch
8. `git checkout` to switch to another branch
    1. Tip: use `git -b checkout` to create a new branch and switch to it
9. `git stash` to remove all local changes in working directory since the last commit

#### .gitignore
All files and folders you add to the .gitignore file will not be checked into version control.

#### Further Reading
1. [GitHub's Git Handbook](https://guides.github.com/introduction/git-handbook/)
2. [Atlassian's Intro to Git](https://www.atlassian.com/git)