![UOGLogo](IMG-All/uoglogo.jpg)

# Setting up Git for use on the Command line
This guide will give a brief overview of how to download and use Git on the command line, which is useful for controlling versions of your working directories on servers etc.

## Download Git for Windows

1. Browse to the official Git website: https://git-scm.com/downloads

![Sshkey](IMG-All/IMG-GitSetup/2-Download.PNG)

## Open Git Bash
Once installed you can open Git Bash from the windows start menu

![Sshkey](IMG-All/IMG-GitSetup/bash.png)


## Account Setup
Once you have installed Git on your device, you will need to configure your GitHub settings so that you can access your repositories and push commits to them.

When you have opened Git Bash you will need to type the following, filling in your GitHub details in place of `YOUR NAME` and `YOUR EMAIL` etc.

```bash
git config --global user.name "YOUR USERNAME"
```
and 
```bash
git config --global user.email "YOUR EMAIL"
```

## Getting to the right folder
Next we need to navigate to where we want to pull the repository to. 

We will have to use the `cd` command to **C**hange **D**irectory, to our github folder. Type in the following command, but replace the directory with your own.

```bash
cd C:\Users\Dan\Documents\GitHub
```

## Cloning your tutorial repository 
You can now clone you tutorial repository that was generated from GitHub Classrooms:

- Go to the Repository page on Github
- Click on Download
- Click Download via SSH
- Copy the contents of the text box
- Type the following command, replacing `YOURREPOSITORY` with the text you just copied!

![Clonerepo](IMG-All/IMG-GitSetup/clonerepo.PNG)

```bash
git clone YOURREPOSITORY
```

## Jupyter Notebook
Move onto the next tutorial which contains some Python Exercises!
