# GitHub Tutorial

By: Xavier Abreu
---
### Git vs. GitHub
_Git:_

Git is a open-source software that allows a person to take a "snapshot" of the persons code. Git also allows you to send and retrieve files folders from the remote (an external repository). Git is used in a command line also known as the terminal. This allows you to work and save codes/projects that you are working on.

_Github:_

Github is a software repository hosting website that uses git to code or make projects. A collabration platform that developers can use to help and learn from each other. It is a system that allows people to work together. Github uses a cloud that can save and retrieve folders. 


---
### Initial Setup
Now that you have a better view of the difference between Git and Github, it is time to put it into use. In order for you to setup your github account, follow these rules:

1. Go to Github.com to sign up.

2. Sign up by adding a username and your password(in terms of hstat students, your email must be your first name, the first letter of your last name, the last 4 numbers of your student id, and finish it with @hstat.org. An example is Johnt9906@hstat.org).

3. Now that you have an account, go to your email account to verify it with github. 

4. Now to connect github and c9, go to github.com and into settings.


---
### Repository Setup
Your done signing up, whats next? How about we start making a repository and pushing it up.

A repository is a directory (basically a folder) but initilized into git. To make a repository you...

1. Make a folder in the terminal by typing `mkdir "name of folder".

2. A common mistake people make is making a folder without entering the folder. To enter the folder type cd "name of folder". To make sure that you are in the folder, it should say ~/workspace/"name of folder" (master).

3. Type `git init` to turn the directory into a repository.  

4. Make a file using `touch.txt`. 

5. Type/ edit in your file.  

6. Type `git add` to add the current file to prepare for commiting.  

7. Type `git commit -m "the message of the snapshot"` to make a snapshot to the projects history.  

8. Type `git push -u add origin to push your repository` into your cloud.  


---
### Workflow & Commands
There are 4 **VERY IMPORTANT** git commands that you need to know in order for your coding to work. Without these commands, you are not getting anywhere. You might not know what they are but that is what I am here for. The 4 commands are status, add, commit, and push.

_Git Status:_

A command that tells which files have been created or changed since the last commit. It will also show which files are in the staging area (red or green).

_Git Add:_

This command adds the current file you are in to prepare for commiting. It tells git that you want to include all the changes/updates that you made to a file into the commit.

_Git Commit:_

This command makes a snapshot of the added files to the projects history. After the snapshot you wil be giving the update a message of the changes that happened. This message has to be in present tense. An example is git commit -m "Change name from ____ to ____". The message will help you understand what you did just in case you forget.

_Git Push:_

This command pushing your commits from your local up to the external storage aka the cloud.