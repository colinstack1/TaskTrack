# ICA04 Reflection

## 1. Local and Remote Repositories

What is the difference between the local TaskTrack repository and the repository hosted on GitHub?

The local TaskTrack repositpry is stored onmy computer and cintains the files and Git history that I worked on directly. The repository hosted on Github is the remote version stored online. The local is where I make changes and commits, while Github allows the project to be backed up and shared and synchronized with other copies of the repository.

## 2. Connecting and Pushing

Why did adding `origin` not immediately place the project files on GitHub?

Adding the origin only creates a connection between the local repository and the Github repository. It does not auto upload any files. I still have to use git push to send my local commits and project files to Github

## 3. Cloning

How is cloning a repository different from downloading its files as a ZIP archive?

Cloning a repository copies both the project file and the Git repository info, which includes the commit history and the connection to the remote repository. Downlading a zip file only gives me the project file and does not include the Git history or automatically connect the folder to Github

## 4. Fetching and Pulling

What information did `git fetch` update, and what additional action did `git pull` perform?

Git fetch checks the remote repository and updates my local info about any new commits or changes on Github wihtou changing my current files. Git pull does this as well, but it aslo brings the remote changes into my current local branch so my working copy is updated

## 5. Focused Commits

Why is it useful to commit the Python feature, sample task data, and README documentation separately?

It is useful to commit the python feature, simple task data, and README documentation separately because each commit represents one specific type of change. THis makes the commit history easier to understand and makes it easier to identify, review, undo, any change if there is a problem later on 