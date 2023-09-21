# GIT project

### In this project I am familiarizing myself with the basics of using git. come along as you learn with me

first of all, what is git?

In my understanding, git is a very powerful **distributed** version control system. 

As a distributed system redundancies is controlled and collaboration between developers is seamless.

To be able to use git it must be installed on your computer either a Windows, Mac, or Linux system.

### Creating my Git repository

First of all, I created a local working directory named **Devops** using ***mkdir*** 

afterward, I changed my working directory to the new directory I created using the ***cd Devops*** 

next i initialize my git using ***git int*** command 

all these steps is in the image below

![1  create a git repository](https://github.com/brightfav/git-project-2/assets/107005839/b2cdb868-c7f5-42df-b4f3-b1757168ffbb)


### making my first commit

in the first step, I initialized git in my working directory next I will have to make my first commit.

what is a commit?

whenever a commit is made in git a **snapshot** of the present state of my repository is taken and a copy is saved in the .git folder in my working directory.

#### step to making my first commit

1. using the command ***touch index.txt*** I create a file index.txt in my working directory

2. I typed a string of text in my ***index.txt*** file

3. using the command ***git add .*** i add the changes i made in my ***index.txt*** file to git staging area

4. I run ***git commit -m "initial commit" to commit my changes to git.

in step 4 adding the ***-m*** flag enables the addition of a comment to the command ensure to make it as descriptive as possible. it is best practice to always state a reason for the commit being made.  

![2 making a commit](https://github.com/brightfav/git-project-2/assets/107005839/fff52bfb-68c0-4442-8802-08914916b491)


### Work with branches

a branch in git helps create different copies of my source code which will enable me to make changes to it without affecting my original code.

to create a new branch I use ***git checkout -b new-branch-name***

the image below shows the output of the command














