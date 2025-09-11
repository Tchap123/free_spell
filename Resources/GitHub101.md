# GitHub 101

## Description
- All Github commands in *Git Bash* or *terminal* to eae your daily life.
- Github is a version control tool for your projects.
- It uses git commands to perform various functions. It ranges from **SETUP**, **STAGING**, **BRANCHING**, and many other functions.
- You can also use GUI for all OS, but that defeats the purpose of this tutorial.


## Lets Get Started
### Setup *(Setting up your initials and Environment)*
1. First open terminal(in linux/MacOS)and install git using below command. For Windows install [**Gitbash**](https://git-scm.com/downloads).
		```sudo apt install git```
2. Next in the terminal, **navigate** through the folder using `cd`,`ls` and `mkdir`, where you want to initialise the git.
3. Next use the command to **initialise the folder** with git:
		```git init```
4. The folder is initalised with git, now you can setup you account.
5. Use the command and enter you `username` and `email`(optional):
		```git config --global user.name "[Firstname Lastname]"```
		```git config --global user.email "[github-email]"```
6. Enter the password using the command below:
		```git config --global user.password "[Acc-password]"```
7. Next you can **clone your repository** or other repository to work on, using: 
		```git clone [url]```
8. The repository will be cloned and you can work on it. After you have made changes you would want the **changes to reflect** on the main branch. So, you use the command:
		```git add --all```
	This command will record all the changes in the files or folders and prepare them.
9. **(Optional)** You can also check the status using:
		```git status```
10. To commit the changes to your branch of the repo, you use the command:
		```git commit -m "[optional message]"
11. To finally push to the main branch of you repo you can use the command:
		```git push```
12. Your changes will reflect on the main branch of your repo.