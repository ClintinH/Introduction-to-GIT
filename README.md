# Introduction-to-GIT
## Learning to use GIT
This is my first attempt to use a **repo** with coding
I managed to create the **repo** and create a *SSH* link to be able to communicate with the **repo**.

## Upgrading my understanding of ***DEV*** Flow
### Repository
Storing your project on a “cloud server” which a group of people can access the project and work on their tasks locally. Pushing their task to the repo for final build.

Git Commands
1. Commit (save latest changes to local Repo)
2. Pull - The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows. [Reference](https://www.atlassian.com/git/tutorials/syncing/git-pull)  
3. Push - The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. [Reference]( https://www.atlassian.com/git/tutorials/syncing/git-push)
4. Fetch (Check latest updates on the main Repositor)
5. Keeps History of changes / projects

### Github
It is a public repository for use. You can make projects that anyone can comment or make changes to or keep it private for personal or group use. 

### Control Systems
**GIT** – Git is a distributed version control system - which just means that when you do a git clone (+url of your repository) what you are actually getting is a complete copy of your entire history of that project. This means all your commits! Woot! [Reference](https://blog.hackbrightacademy.com/blog/svn-vs-git/)

**SVN** – Subversion (SVN) may be one of the most well known centralized version control systems. In Subversion or SVN, you are checking out a single version of the repository. With SVN, your data is stored on a central server. Having the entire history on your local repository just means that even when you are not connected to the Internet, you can still do commits, diffs, logs, branches, merges, file annotations, etc. [Reference]( https://blog.hackbrightacademy.com/blog/svn-vs-git/)

**What is difference between SVN and Git repository?**

The difference between Git and SVN version control systems is that Git is a distributed version control system, whereas SVN is a centralized version control system. Git uses multiple repositories including a centralized repository and server, as well as some local repositories. [Reference]( https://blog.hackbrightacademy.com/blog/svn-vs-git/)

**Gitignore** – file tells Git which files to ignore when committing your project to the GitHub repository. gitignore is located in the root directory of your repo. [Reference]( https://www.bmc.com/blogs/gitignore/#:~:text=gitignore%20file%20tells%20Git%20which,is%20a%20plain%20text%20document.)

### Difference between staged and unstaged commits
Unstaged changes are changes that are not tracked by the Git. For example, if you copy a file or modify the file. Git maintains a staging area(also known as index) to track changes that go in your next commit. The staging area is a file, in your Git directory, that stores information about what will go into your next commit. Staging the changes will put the files into the index. The next git commit will transfer all items from staging into your repository. [Reference]( https://www.testingdocs.com/questions/what-are-unstaged-and-staged-changes-in-git/)

### What is a Branch
A branch represents an independent line of development. Branches serve as an abstraction for the edit/stage/commit process. You can think of them as a way to request a brand new working directory, staging area, and project history. New commits are recorded in the history for the current branch, which results in a fork in the history of the project.The git branch command lets you create, list, rename, and delete branches. It doesn’t let you switch between branches or put a forked history back together again. For this reason, git branch is tightly integrated with the git checkout and git merge commands. [Reference]( https://www.atlassian.com/git/tutorials/using-branches#:~:text=A%20branch%20represents%20an%20independent%20line%20of%20development.) 
### What is a SSH key
SSH keys come in many sizes, but a popular choice is an RSA 2048-bit encryption, which is comparable to a 617 digit long password. SSH keys always come in pairs, and every pair is made up of a private key and a public key. Who or what possesses these keys determines the type of SSH key pair. If the private key and the public key remain with the user, this set of SSH keys is referred to as user keys.
If the private and public keys are on a remote system, then this key pair is referred to as host keys. Another type of SSH key is a session key. When a large amount of data is being transmitted, session keys are used to encrypt this information. [Reference]( https://jumpcloud.com/blog/what-are-ssh-keys)

### What license should be used for coding projects
GNU Public License
Always use a GPL-compatible license.

Perhaps the best-known license is the GNU Public License (GPL), which guarantees the freedom of users to use, copy, and modify code. Code released under a GPL-compatible license is code that can be incorporated into another GPL-licensed codebase without modification to the license. [Reference](https://www.astrobetter.com/blog/2014/03/10/the-whys-and-hows-of-licensing-scientific-code/)