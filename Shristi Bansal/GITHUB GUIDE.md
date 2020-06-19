# TASK-5
## STEP BY STEP GITHUB GUIDE.
 
### This document contains everything about git and github including its working, use, commands and features.


### WHAT IS GIT?

Git is a free, open source distributed version control system tool designed to manage a development project's source code history with efficiency. It is a tool a developer installs locally on their computer. It was created by Linus Torvalds in 2005 to develop Linux Kernel. Git has the functionality, performance, security and flexibility that most teams and individual developers need.


### WHAT IS GITHUB?

GitHub is a highly used software which is typically used for version control. It is helpful when more than just one person is working on a project. Say for example, a software developer team wants to build a website and everyone has to update their codes simultaneously while working on the project. In this case, Github helps them to build a centralized repository where everyone can upload, edit and manage the code files. Github has many advantages over other cloub based sites like dropbox. Github document the changes and reflect them in an organized manner to avoid any chaos between any of the files uploaded.
GitHub is a Git repository hosting service, which provides a web-based graphical interface. It is so popular and used in most of the projects because of the following reasons:-
a)Open, clear communication
b)Public APIs. These allowed others to build upon their work.
c)The right amount of functionality: repo, issue tracking, wiki, GitHub Pages
d)Developer Oriented
e)Superb technology choice: Git
f) Better than other alternatives


### WHAT IS GITBASH?

Git Bash is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience. Bash is an acronym for Bourne Again Shell. A shell is a terminal application used to interface with an operating system through written commands.


### HOW GITHUB WORKS?

GitHub is a Git repository hosting service, which provides a web-based graphical interface. It helps every team member to work together on the project from anywhere and makes it possible for them to work collaboratively.
It is used widely by software developers as it allows them to store source codes for a project and track the complete history of all changes to that code. There are millions of repositories on GitHub and each repository has its own tools to help you host and release code.
GitHub helps all the team members to stay on the same page and stay organized. Moderation tools like issue and pull request locking help the team to focus on the code. GitHub is one place where project managers and developers coordinate, monitor, and update their work so projects stay transparent and on time.
Pull requests help the teams to review, improve, and propose new codes on GitHub. The implementations and proposals can be discussed before changing the source code.
The packages can be published privately, or within the team or publicly for the open-source community. The packages can be used or reused by downloading it from the GitHub.
GitHub uses tools to identify and analyze vulnerabilities to the code, that other tools tend to miss. Development teams everywhere work together to secure the software supply chain, from fork to finish.


### ELEMENTS OF GIT WORKFLOW?

Git Workflow consist of the four fundamental elements: 
•  **Workspace**(also known as Working Directory) and if we consider a file, it can have 3 states:
 (a)Committed : meaning latest changes in the data is stored in local repo.
 (b)Modified: means the changes are done but are not securely stored or will not be reflected in local repository.
 (c)Staged: meaning file is part of index element.

• **Index**(also known as Stage)
• **Local Repository**(also known as Head)
• **Remote Repository**

**CLONE COMMAND**: If we are gaining access to a remote repository then we need to clone it by following it by URL using git clone command which will create a local cpopy of repository in our workspace.

**ADD COMMAND**: This command will add the file in the workspace in the index stage and thus we call this file as staged file.

**COMMIT COMMAND**:  This command will commit all files that are staged with their changes and are safely stored.
               We can perform these add and commit commands in a single defined command as commit -a which helps in commiting all files at once if they are part of repository and already known.

**PUSH COMMAND**: It pushes the changes that are in the local repository to the remote repository and anyonce having access to this remote repo can see the changes.

For opposite flow we have following commands:

**FETCH COMMAND**: Used to get files from the remote repository to local repository.
**MERGE CAMMAND**: It get changes from local repo and get them to workspace.
**DIFF COMMAND**: Used to tell the difference between files which are in workspace and ones which are stagged for commit.


### GETTING STARTED

Download and install git from https://git-scm.com



### CREATING A GIT REPOSITORY


(a) Go to the account and click option NEW repository.

(b) We can give a repository name and make a README file

(c) Then in gitbash, enter the repository by writing `<cd repo_name>`.

(d) Then for initializing this repository, use command : `<git init>`

(e) Make a file inside this repo and add this your repo using `<git add .>` command

(f) Then for commiting it use command : `<git command -m "Message here">`

(g) Then push it to the repository using command : `<git push -u repo_name master>`.

### FORKING

A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.When you fork a repository, it’s a clone of the entire repository within GitHub with all of its branches. Typically you do a fork if you want to use the current repository as a base to work on a new project or make changes to show differences between the current repository and the new one in large open source projects.
We can fork any repository by clicking the fork option on the right side of the repository.


### CLONING

Clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository.When you create a new repository on GitHub, it exists as a remote location where your project is stored. You can clone your repository to create a local copy on your computer so that you can sync between both the local and remote locations of the project. Cloning is ideal for instances when you need a way to quickly get your own copy of a repository where you may not be contributing to the original project.
For cloning the repository, we need to use command line and provide the following command:

(a) First go the repository 

(b) Then click clone or download option under repository.

(c) Copy the URL name.

(d) use command `< git clone <LINK> >`


### WHAT ARE PULL REQUESTS?

A pull request (PR) is a method of submitting contributions to an open development project. It occurs when a developer asks for changes committed to an external repository to be considered for inclusion in a project’s main repository after the peer review.
The git pull command is used to merge a different repository into your local one. So if someone else has a copy of your git repository, and makes changes to it that they would like you to incorporate, they can ask you to pull the changes from their repository; they're requesting a pull, hence the term- pull request.


### HOW TO MAKE A PR?

(a) Clone a repository

(b) Enter the cloned repository from your account.

(c) Make a directory using command `<mkdir>`.

(d) Enter the directory using command `<cd directory_name>`.

(e) Add some text files in this directory by either physically going to it in your system or by command : echo "Content" > fileName.txt

(f) Now using command : `<git add fileNme.txt >`, add the file.

(g) Commit the file: `<git commit -m "Message">` 

(h) Now push it to the repository using command : `<git push origin master>`.
  Here if we are doing this by making any other branch, We need to push it by first usng git pull command and then by using `<git push --set-upstream origin branch_name>`.

(i) Now go the repository and click Create pull request option.

(j) Provide a good name for PR and a good description as well, and then Click option Compare and then see the base and head repository.

(k) Click create pull request and your PR will be opened until and unless the head of the repository merges it.


### WHAT IS A BRANCH?

A branch is simply a pointer to one of the commits in the repository.  Git branch is a feature in git used for separating a feature or part of code from you your master in order not to mess something in your main code like suppose you have a website as a project in git and you want to add a new feature to it so you do it by creating a new branch for it so your main code remain the same as it and once you complete it then you merge it with your master.


### CREATING A BRANCH 

Use command :
`<git branch branch_name>`

To enter into a branch use command :
`<git checkout branchname>`

To see list of all branches in your project use command :
`<git branch -ls>`

To delete a branch, use command :
`<git branch -d branch_name>`


### MERGE CONFLICTS

 In Git, "merging" is the process of combining another branch into our current working branch. We are taking changes from another context  and combining them with  current working files.
 However, there are some situations where we might have tell Git what to do while merging. This is when changing the same file. In this case, if two people changed the same lines in that same file, or if one person decided to delete it while the other person decided to modify it, Git simply cannot know what is correct. Git will then mark the file as having a conflict 
 This is known as merge conflict.
 A merge conflict is an event that occurs when Git is unable to automatically resolve differences in code between two commits.
 Merge conflicts can happen when merging a branch, rebasing a branch, or cherry picking a commit.


### CREATING A MERGE CONFLICT

(a) Either make a git repository or enter into your git repository using cd command and initialize it using : `<git init>`.

(b) Now make a text file names merge.txt and add content to it.

(c) Add this by using `<git add merge.txt>`

(d) Commit it by using   `<git commit -m "Message">`

(e) Now, one file name with content is made in the repository.

(f) Now make a new branch and enter into it using command " `<git checkout -b newbranch> .

(g) Override the content in merge.txt file.

(h) Now add and commit it using : `<git add merge.txt>` and `<git commit -am "Message">`

(i) Now enter your master branch using : `<git checkout master>`

(j) Now write `<echo "Content to append" >> merge.txt>`

(k) commit it

(l) Now write :  `<git merge newbranch>`.

A conflict will occur. This is called a merge conflict when we are trtying to change content of the file in same line together and trying to commit.


### HOW TO VIEW MERGE CONFLICT

(a)Use command : `<git status>` to see the merge conflict.

(b)The  use `<cat merge.txt>` to see the conflict and its cause.

 Many signs like <<<<<<<, >>>>>>> and ======== will appear.
 These are called conflict dividers and we need to erase them to solve the merge conflict.


### RESOLVING MERGE CONFLICT

(a) To solve the merge conflict, we need to open the text file called merge.txt.
(b) After entering the file, we need to delete all the conflict dividers\
(c) After deleting it, save the file and write command: `<git commit>` and then push it.

Merge conflict is resolved.


### WHAT IS AN ISSUE?

Issues shown in github is the way to track the problems while using the code in repository. Anybody use the code can raise issues and responsible people will take it forward to fix the problem after verifying. It can also be used to keep track of tasks, enhancements for the code base.


### CREATING ISSUE IN GIT

(a) To create an issue, clone a repository or make it in your own repository.
(b) Go to the option issue.
(c) Give a good name to your issue and a good description to it.
(d) We can add labels to it by which we can tell which kind of issue it is.
(e) We can also make our own label.
(f) Then click Create issue and your issue is created/opened.
(g) We can add comments to it and can resolve it.