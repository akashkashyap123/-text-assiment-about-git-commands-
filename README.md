# -text-assiment-about-git-commands-
all about git commands , why we use git  commands nd what those  commands  dos 
Why should you use Git?
  
    • It helps to make collaborations also makes to multiple people to merge into one source.
    • It helps to have record on what has been done.
      • It helps to keep track on changes made in code.
    • It helps to develop new code and push.
    • It helps to save easily all versions on git.
    • It easily shift to low versions from high version.

What is the benefit of distributed version control?
    • Atomatically branching and merging is possible.
    • Users can work offline.
    • Multiple copies on single backup.
    • Speed can be more.

What is the command for installing Git on your Linux system?
    • sudo apt install git -all

Why should you set up user.name and user.email configuration? How do you set them up?
    • To change git identity
    • git config –global user.name “username”
    • git config –global user.email “emailid”

Can you define working directory,staging, repository and remote repository?
    • Working directory-It is current local directory your working on.
    • Staging-In this stage, the file is ready to be committed and is placed in the staging area waiting for the next commit
    • Repository-When ever we start a project, we will need to store all files in a repository.The .git folder is your local repository and it stores all history and version control   information
    • Remote repository-A Git repository is a virtual storage of your project. It could be a seperate other machine/Computer or server. It allows you to save versions of your code, which you can access when needed.
Can you draw how documents move from one stage to another?
Untracked                    unmodified                      modified                     staged

|---add the file---------------|--------------------------------|-------------------------->|
                                           |------edit the file -->                |---stage the file-->  |
     <-----Remove the file---|<----------------------commit-------------------------- |

      
How do you initialize a directory to be tracked by Git?
    • git init <directory>
      
What does git status do?
    • On branch master 
    • Initial commit
    • nothing to commit(create/copy files and use “git add”to track)

What does git log do?
    • Fatal:your current branch ‘master does not have any commits yet


What does git status do?

    • The git status command displays the state of the working directory and the staging area. 
    • It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. 
    • Status output does not show you any information regarding the committed project history.
      
What does git log do?
    • The git log command shows a list of all the commits made to a repository. 
    • You can see the hash of each Git commit, the message associated with each commit, and more metadata. 
    • This command is useful for displaying the history of a repository.

What does git add do?
    • It adds all modified and new (untracked) files in the current directory and all subdirectories to the staging area (a.k.a. the index), thus preparing them to be included in the next git commit .
    •  Any files matching the patterns in the . gitignore file will be ignored by git add .

What does git commit do?
    • The git commit command is used to move files from the staging area to a commit. This command is run after git add, which is used to add files to the staging area.
    • The git commit creates a snapshot of the changes made to a Git repository which can then be pushed to the main repository when the developer is ready to do so.
How to push file to remote reopsitory?
    • By using the command - git push origin (branch name)
    • Giving user name and password as token


Why do you need branching?

    • Essentially creating a timeline of versions of a project as it progresses, so that you can roll back to an earlier version in the event disaster strikes. 
    • The way git, and GitHub, manage this timeline — especially when more than one person is working in the project and making changes — is by using branches.


Which command is used to create branch?

    • The git branch command can be used to create a new branch. When you want to start a new feature, you create a new branch off main using git branch new_branch . 
    • Once created you can then use git checkout new_branch to switch to that branch.

What does checkout means?

    • Checkout is the command used to switch between the different branches of a GitHub repository. 
    • When a branch is checked out, all files in the working directory are updated to match the versions stored in that branch.



How to delete branch?
    
You can have head branches automatically deleted after pull requests are merged in your repository. For more information, see "Managing the automatic deletion of branches."
    • Note: If the branch you want to delete is the repository's default branch, you must choose a new default branch before deleting the branch. For more information, see "Changing the default branch."
    • If the branch you want to delete is associated with an open pull request, you must merge or close the pull request before deleting the branch.



Why we create pull request?
    • Reviews allow collaborators to comment on the changes propsed in pull requests, approve teh changes , or request further changes before the pull request is merged. Repository administators can require that all pull requests are approved before being merged.



Why we do review?
    • Git code reviews are important for many reasons: Making sure the code works and meets requirements 



When and who merge the pull request?
    • In a pull request, you propose that changes you've made on a head branch should be merged into a base branch.
    •  By default, any pull request can be merged at any time, unless the head branch is in conflict with the base branch.
