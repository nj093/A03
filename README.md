# A03
  
Git and GitHub are not the same thing. Git is an open-source, version control tool created in 2005 by developers working on the Linux operating system; GitHub is a company founded in 2008 that makes tools which integrate with git. You do not need GitHub to use git, but you cannot use GitHub without using git. There are many other alternatives to GitHub, such as GitLab, BitBucket, and “host-your-own” solutions such as gogs and gittea. All of these are referred to in git-speak as “remotes”, and all are completely optional. You do not need to use a remote to use git, but it will make sharing your code with others easier.  
  
## Git and GitHub  
Step1 - Install the Git  
On your terminal enter  
`git --version`  
If you don’t have it installed already, it will prompt you to install it.
  
Step2 - Create a local git repository 
To begin, open up a terminal and move to where you want to place the project on your local machine using the cd (change directory) command.
To initialize a git repository in the root of the folder, run the git init command:  
`git init`
  
Step3 - Add a new file to the repo  
Go ahead and add a new file to the project, using any text editor you like or running a touch command. 
`touch mnelson.txt`  
  
Step4 - Add a file to the staging environment
Add a file to the staging environment using the git add command. 
`git add`  
`git status`  
  
Step5 - Create a commit  
Run the command git commit -m "Your message about the commit"
`git commit -m "This is my first commit!"`
  
Step6 - Create a new branch  
Now that you've made a new commit, let's try something a little more advanced.
Say you want to make a new feature but are worried about making changes to the main project while developing the feature. This is where git branches come in. 
Branches allow you to move back and forth between 'states' of a project. Official git docs describe branches this way: ‘A branch in Git is simply a lightweight movable pointer to one of these commits.’ For instance, if you want to add a new page to your website you can create a new branch just for that page without affecting the main part of the project. Once you're done with the page, you can merge your changes from your branch into the primary branch. When you create a new branch, Git keeps track of which commit your branch 'branched' off of, so it knows the history behind all the files.  
`git branch`  
  
Step7 - Create a new repository on GitHub  
To create a new repo on GitHub, log in and go to the GitHub home page. You can find the “New repository” option under the “+” sign next to your profile picture, in the top right corner of the navbar. After clicking the button, GitHub will ask you to name your repo and provide a brief description.    
  
Step8 - Push a branch to GitHub  
Now we'll push the commit in your branch to your new GitHub repo. This allows other people to see the changes you've made. If they're approved by the repository's owner, the changes can then be merged into the primary branch.
To push changes onto a new branch on GitHub, you'll want to run git push origin yourbranchname. GitHub will automatically create the branch for you on the remote repository
  
Step9 - Create a pull request   
A pull request (or PR) is a way to alert a repo's owners that you want to make some changes to their code. It allows them to review the code and make sure it looks good before putting your changes on the primary branch.
  



## Glossary
* **Branch** - In Git, a branch is a pointer to a specific commit. The branch pointer moves along with each new commit you make, and only diverges in the graph if a commit is made on a common ancestor commit. There are various commands you can take in Git to work with your branches.  
* **Clone** - The "clone" command downloads an existing Git repository to your local computer. You will then have a full-blown, local version of that Git repo and can start working on the project.  
* **Commit** - The git commit command captures a snapshot of the project's currently staged changes. Committed snapshots can be thought of as “safe” versions of a project—Git will never change them unless you explicitly ask it to. ... These two commands git commit and git add are two of the most frequently used.  
* **Fetch** - The git fetch command downloads commits, files, and refs from a remote repository into your local repo. Fetching is what you do when you want to see what everybody else has been working on. ... This makes fetching a safe way to review commits before integrating them with your local repository.  
* **GIT** - Git is a mature, actively maintained open source project originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel. A staggering number of software projects rely on Git for version control, including commercial projects as well as open source. Developers who have worked with Git are well represented in the pool of available software development talent and it works well on a wide range of operating systems and IDEs  
* **Github** - GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features  
* **Merge** - Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.  
* **Merge Conflict** - A merge conflict is an event that occurs when Git is unable to automatically resolve differences in code between two commits. When all the changes in the code occur on different lines or in different files, Git will successfully merge commits without your help.  
* **Push** - The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.  
* **Pull** - The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. The git pull command is actually a combination of two other commands, git fetch followed by git merge.  
* **Remote** - A remote repository in Git, also called a remote, is a Git repository that's hosted on the Internet or another network. The video will take you through pushing changes to a remote repository on GitHub, viewing a remote's branches, and manually adding remote.  
* **Repository** - Repository contain a collection of files of various different versions of a Project. These files are imported from the repository into the local server of the user for further updations and modifications in the content of the file.  

## References  
1. [Gitkraken](https://www.gitkraken.com/learn/git/tutorials/how-to-git-branch)  
2. [GitTower](https://www.git-tower.com/learn/git/commands/git-clone)  
3. [Atlassian](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)  
4. [TechCrunch](https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/)  
5. [Geeksforgeeks](https://www.geeksforgeeks.org/what-is-a-git-repository/)  
6. [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)  
7. [OpenSource](https://opensource.com/article/18/1/step-step-guide-git)  
