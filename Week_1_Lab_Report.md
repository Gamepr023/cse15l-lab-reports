# Week 1 Lab Report
This is a tutorial on how to log into `ieng6`, a UCSD CSE 15L course-specific account using Remote Access.

## **Step 1: Installing Visual Studio Code**
This is the main program that will be used in this course. Install [VSCode](https://code.visualstudio.com/) and open it when it is done installing. It should look something like this:

![image](VSCodeScreenshot.png)

## **Step 2: Installing Git Bash**
Git Bash is the terminal that will be used to access the course account. Install [git](https://gitforwindows.org/) and go through the installer. Once installed, you can open the git bash terminal through VSCode by opening a new terminal with Ctrl + ` or clicking on *Terminal* at the top of the window and clicking on new terminal. 

![image](TerminalScreenshot.png)

Then press the down arrow next to the plus sign here, and select *Git Bash*.

![image](GitBashTerminalScreenshot.png)

## **Step 3: Connecting to the Account**
Find your CSE 15L account using this link: https://sdacs.ucsd.edu/~icc/index.php

To reset your CSE 15L account password, follow this tutorial: [[TUTORIAL] How to Reset your Password](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit)

---

Once you have your account details, in the terminal, make sure to type: 

`$ ssh cs15lwi23___@ieng6.ucsd.edu`

The dollar sign will be there already and remember to replace the blank space with your own account details.

If this is the first time logging into the server, you will get a message that looks like:

```
$ ssh cs15lwi23___@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```
Type yes and press enter. Then, type in your password and press enter. It is normal for the terminal to not show you what you are typing, but it will still log you in. 

## **Use the Terminal to Run Commands**
If your terminal looks like:

```
Hello cs15lwi23___, you are currently logged into ieng6-202.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   14:30:01   13  0.35,  0.14,  0.13
ieng6-202   14:30:01   15  0.25,  0.12,  0.07
ieng6-203   14:30:01   15  0.03,  0.07,  0.10

 
Thu Jan 12, 2023  2:31pm - Prepping cs15lwi23
```

You have successfully connected to the UCSD CSE 15L course-specific account, and all commands will be run on the CSE Server.

Try different commands like:

- `cd` - Change the directory to another path
- `pwd` - Print working directory and displays current path
- `ls` - Prints all files and folders in a path
- `cat` - Prints contents of all files in a path
