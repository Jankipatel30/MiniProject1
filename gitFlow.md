Let's start to understand gitFlow
gitFlow is a branching model for Git.It is very well suited to collaboration and scaling the development team.
Key Benefits:
1. Parallel Development : GitFlow is that it makes parallel development very easy, 
                          by isolating new development from finished work.
2. Collaboration : Feature branches also make it easier for two or more developers to collaborate on the same feature, because each feature branch is a sandbox where the only changes are the changes necessary to get the new feature working. 
                   That makes it very easy to see and follow what each collaborator is doing.
3. Release Staging Area : As new development is completed, it gets merged back into the develop branch, which is a staging area for all completed features that haven’t yet been released.
                          So when the next release is branched off of develop, it will automatically contain all of the new stuff that has been finished.
4. Support For Emergency Fixes : GitFlow supports hotfix branches - branches made from a tagged release. 
                                 You can use these to make an emergency change, safe in the knowledge that the hotfix will only contain your emergency fix

Now Let's start to understand Git Commands
## *Repository* :
Git manages the set of projects, as they change over time. Git stores this information in data structure called Repository.
Your Project's repository contains all of your project's file and stores each file's revision history.
For user-owned repositories, you can give other people collaborator access so that they can collaborate on your project. 
If a repository is owned by an organization, you can give organization members access permissions to collaborate on your repository. 
![Repository](/Images/Repository.png)

## *git config*
Configure the author name and email address to be used with your commits.
    git config --global user.name "Name"
    git config --global user.email "Email address"
![config](/Images/config.png)

## *git init*
This command is used to start a new repository.
	git init[Respository Name]
![init](/Images/init.png)

## *git clone*
Create a local copy in your computer from your remote repository.
    git clone [URL]
![clone](/Images/clone.png)

## *git fork*
Forks are used to either propose changes to someone else's project or to use someone else's project as starting point of your own idea.
![fork](/Images/fork.png)

## *git branch*
List all the branches in your repo, and also tell you what branch you're currently in.
    git branch
Create a new branch and switch to it:
    git checkout -b <branch name>
Switch from one branch to another:
    git checkout <branch name>

## *git commit*
This command records or snapshots the file permanently in the version history.
This command commits any files you've added with the git add command and also commits any files you've changed since then.
	git commit -a

## *git checkout*
Switch branches or restore working tree files
   git checkout <branch name>

## *git merge*
To merge a different branch into your active branch.
    git merge <branch name>

## *git push*
Push all branches to your remote repository:
    git push --all origin
This command sends the committed changes of master branch to your remote repository:
    git push [variable name] master
Delete a branch on your remote repository:
    git push origin :<branch name>

## *git pull*
Fetch and merge changes on the remote server to your working directory.
    git pull

## *git remote*
If you haven't connected your local repository to a remote server, add the server to be able to push to it.
    git remote add origin <server>
List all currently configured remote repositories:
    git remote -v

## *git show*
Show various types of objects.
    git show [<options>] [<object>…​]

## *git add*
After you have manually resolved any conflicts, you mark the changed file.
    git add <filename>

## *git remove*
If you want to remove a remote for some reason- you've moved a server or no longer using the particular mirror, use:
    git remote remove

## *git status*
List the files you've changed and those you still need to add or commit.
    git status



Credit :
https://datasift.github.io/gitflow/IntroducingGitFlow.html
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html
https://help.github.com/en/articles/about-repositories'