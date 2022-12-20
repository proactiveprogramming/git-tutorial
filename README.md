
![](https://upload.wikimedia.org/wikipedia/commons/2/29/Git-Logo-2Color.png) 

# git-tutorial
Git (/ɡɪt/)[8] is a distributed version control system: tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).

This tutorial is designed to learn Git and GitHub.  It contains a couple of simple example files to work with.  It also includes other files that are included when setting up an Git environment.

## What are the branches for ...

* main - the stable branch.  Only stable releases should be put into this branch. (long term branch)
* dev - the development branch.  As features and bugfixes are completed, they are merged into the dev branch. (long term branch)
* Release-x (Release-1.0) -- Temporary branch that is used to prepare for a formal release until it is ready to be merged into the main branch..  It is merged into the dev branch.  Once a release branch is created, no new features are added to this branch.  Only bugfixes are allowed to be merged into this branch.
* Bugfix-x -- Temporary branch that is used to handle a bug fix.  For very small big fixes, this might not be needed.  But for more complex bug fixes, it can help to keep things separated until they are ready to be merged into the dev branch.
* Feature-x -- Temporary branch that is used to handle adding a new feature until it is ready to be merged into the dev branch.
* Hotfix-x -- Temporary branch that is used to handle a bug fix that MUST be fixed before a regular release.  These are usually related to critical bug fixes that involved security issues or the software does not fuction correct to a level where the customer cannot use the software.

## Learn More from our Wiki pages

* [Git-tutorial Wiki](https://github.com/proactiveprogramming/git-tutorial/wiki)
* [What are the differences between different OpenSource licenses](https://github.com/proactiveprogramming/git-tutorial/wiki/What-are-the-differences-between-different-opensource-licenses)? 
* [Git Cheatsheet](https://github.com/proactiveprogramming/git-tutorial/wiki/Git-Cheatsheet)

## References
**Videos**
* Video: Git and GitHub for Beginners Tutorial by Kevin Stratvert -- (https://www.youtube.com/watch?v=tRZGeaHPoaw&t=1938s)

**Source Files**
* Files: Sample files to follow along -- https://onedrive.live.com/?authkey=%21AJdw967%5FoljMamM&id=B09F9559F6A16B6C%2178117&cid=B09F9559F6A16B6C
* Files: Sample ignore files -- https://github.com/github/gitignore
* Files: Git prompt in terminal window -- https://github.com/git/git/tree/master/contrib/completion
* Files: Example gitignore files -- https://github.com/github/gitignore

**Websites and other info**
* Official Git web site -- https://www.git-scm.com/
* Official GitHub.com web site -- https://github.com/
* Git and GitHub.com cheat sheet -- https://education.github.com/git-cheat-sheet-education.pdf
* Git Reference Manual -- http://git-scm.com/docs
* Git Overview Book -- http://git-scm.com/book/en/v2



