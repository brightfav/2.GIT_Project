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

![3 creating and switching to a  new branch](https://github.com/brightfav/git-project-2/assets/107005839/5324f43c-872d-4320-98e6-8938e75904b4)

so show all the branch in my local git repository i use the command below.

***git branch***

the image below shows all the availabel branch in my local repository

![4 listing all the branch in the local directory](https://github.com/brightfav/git-project-2/assets/107005839/ba81ebc8-4da0-44fc-952b-7d8aba437916)


to change to another branch i typed the command below 

***git checkout branch-name***

in the image below I changed to a different branch

![5 change to another branch](https://github.com/brightfav/git-project-2/assets/107005839/f7ba4fb0-3153-47c4-9f9b-f9b4d7c549d4)


### merging one branch to another

for example I have two brances "alpha" and "beta". if i want to add the content of beta into alpha i will do it as listed below

firstly i will change to branch alpha and run the command below

***git merge beta***

the image below depicts this process

![6 merge two branch together note to always swithch to the branch that will be added to](https://github.com/brightfav/git-project-2/assets/107005839/ff50e580-f66f-457c-8a32-df22ab9981a2)

### Delete a git branch

after a branch has served it's purpose most often the branch is deleted. 

to delete a branch us the command stated below

***git branch d branch-name***

the image below depicts this output

![7 delete a branch](https://github.com/brightfav/git-project-2/assets/107005839/4641eaeb-a18c-47df-8595-4c84dbc0aeaa)



### Pushing my local Git repository to my remote GitHub repository

Before doing this I created a GitHub account and created a remote repository on GitHub.

next i copied my GitHub repo link

next, i typed the command below into my git bash terminal to add my remote repository to my local repository

***git remote add origin my-GitHub-repo-link***

the image below is the output of this command

![8 push local repository to git remote repository](https://github.com/brightfav/git-project-2/assets/107005839/80233650-f633-4778-a09b-79612522d203)

in a process I previously showed I commit my changes to my local repository 

next, I type the command below to push my content from my local repository to my remote repository in GitHub

***git push origin branch-name***

the image below is the output of this command

![9 push commit changes made in local repo to remote repo](https://github.com/brightfav/git-project-2/assets/107005839/e19430fd-c0d0-40ca-b16e-5214bc092c92)

## Cloning Remote Git Repository

this command enables me to clone my remote repository into my local repository.

this is can be a convenient way for developers to work on projects even in the absence of internet connection.

the command below is used to clone remote repository into local machine

***git clone my-github-repo-link***

![10 clone a repo from remote git to local repository](https://github.com/brightfav/git-project-2/assets/107005839/52c5ce48-52b2-4801-94f7-7d20ac1f2576)


