# task 1

** 1. What do you mean by git and github? **
 Git is an extremely popular version control system that is at the heart of a wide variety of high-profile projects. Git is installed and maintained on your local system (rather than in the cloud) and gives you a self-contained record of your ongoing programming versions. It can be used completely exclusive of any cloud-hosting service — you don't even need internet access, except to download it.
In the discussion of Git vs. GitHub, it's been said that GitHub is to Git what Facebook is to your actual face. What's that mean? Well, it means that while Facebook is kind of like an online face database (of sorts). GitHub is designed as a Git repository hosting service.
2. Why GitHub is so popular and used in most of the projects.?
1: Immensely Powerful Community
2: The Largest Shared Repository
3: Easy Version Control
4: A Myriad Of Integrations
5: Secure Cloud Storage
3. What is version control system? How git is a vcs?
Version control systems are a category of software tools that help a software team manage changes to source code over time. Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.Git is a Distributed VCS, a category known as DVCS, more on that later.
...
Benefits of version control systems
A complete long-term change history of every file. This means every change made by many individuals over the years. ...
Branching and merging. ...
Traceability.
4. What are the other platforms similar to github?
There are some good GitHub alternatives, four of which are presented below.
GitLab. GitLab offers many useful features in its DVCS such as an integrated project wiki and a project website. ...
a. SourceForge. ...
b. Cloud Source Repositories. ...
c. GitKraken.
d. Apache Allura.
5. Why are you interested in learning of git and github?
As being a cs engineer not only the academics  are important also the side courses and many learning platforms are necessary and i found git and github one of the best of them..!!


# task 2

**Q.1  How git workflow works?**
-- Git can support your project not just with version control, but also with collaboration and release management. Understanding how Git workflow patterns can help or hinder a project will give you the knowledge to evaluate and adapt your project’s Git processes effectively.
Throughout this guide I will isolate software development process patterns found in common Git workflows. Knowledge of these will help you find a direction when joining, creating or growing a development team. The pros and cons for certain types of projects or teams will be highlighted within the workflow examples we explore, so that you can pick and choose what might work well for your scenario.
Q.2  What are the different stages of git project as commit,add?
  The three stages are as follows ;-
  • Modified:
So, going back to our example, we saw that, those students have messed up their project. So, under Git we can create a repository, a repository is basically a kind of a directory that contains all the files related to your code.
  • Staged:
In the previous section we learnt about modification, now let’s look at the second stage in Git, i.e. staged. So, we saw that we can make changes to the project without hampering the original version, but how do we apply those changes to our remote repository? So, we use the commands in the Git command line — git add. So, this command tracks the new changes and pushes it to the staging area. So, staging area is place prior to the actual implementation of changes, i.e. this area contains all the added files that contain new code, which are ready to be joined to the remote repository.
  • Commit:
This is the final stage, as this stage finally applies the new changes to the remote repository. Looking at the previous analogy, this is your ‘Go’ position. So, a commit is a set of new files that are being added to a project as part of the modification.
Q.3 Is it possible to do a git commit before git add?if no,explain why?
  git commit
The "commit" command is used to save your changes to the local repository.
Note that you have to explicitly tell Git which changes you want to include in a commit before running the "git commit" command. This means that a file won't be automatically included in the next commit just because it was changed. Instead, you need to use the "git add" command to mark the desired changes for inclusion.
Q.4 why is git diff is used?
  Diff command is used in git to track the difference between the changes made on a file. Since Git is a version control system, tracking changes are something very vital to it. Diff command takes two inputs and reflects the differences between them. It is not necessary that these inputs are files only.
Q.5 Can we leave the commit messages as blank?
  git generally requires a non-empty message because providing a meaningful commit message is part of good development practice and good repository stewardship. The first line of the commit message is used all over the place within git; for more, read "A Note About Git Commit Messages". (edited) 

#  task 3

**1. What is meant by the term fork and clone?**
When you fork, you copy someone else's remote repository to a remote repository under your user account name on GitHub. A clone is different in that it copies the remote repository down to your computer, where it's a local repository.
2. What are the branches of github?
The way git, and GitHub, manage this timeline — especially when more than one person is working in the project and making changes — is by using branches. A branch is essentially is a unique set of code changes with a unique name. Each repository can have one or more branches.
3. What is PR?
From Github's Using Pull Requests Page. Pull requests let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.
4. Can we delete the master branch,if not then why?
It is possible to delete the master branch by executing the following steps:-
1.On the GitHub page for your forked repository, and click on the “Settings” button.
2.Click on the "Branches" tab on the left hand side. There's a “Default branch” dropdown list near the top of the screen.
3.From there, select placeholder (where placeholder is the dummy name for your new default branch).
4.Confirm that you want to change your default branch.
5.Use the git command-
git push origin :master
the master branch is deleted.
5.How can we delete a branch?
Delete a branch with git branch -d <branch> . The -d option will delete the branch only if it has already been pushed and merged with the remote branch. (edited) 


