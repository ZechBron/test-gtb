# Test Repo Git Bash - For Windows

This is a sample run for git bash for windows

<!-- https://github.com/ZechBron/test-gtb.git -->


## Description

You don't have to type long commands to upload a file in your github repository. Using EazyGit, you can do it using only one command.


## Full Guide


+ Download Git Bash Here:

Install Git Bash for Windows here:

[Download Link 1](https://gitforwindows.org/)

[Download Link 2](https://git-scm.com/downloads)


+ Now Install EazyGit by typing this commands in Git Bash:

   > git clone https://github.com/ZechBron/EazyGit

   > cd EazyGit

   > bash setup

   Now Choose Git Bash - Windows (Number 3)

+ To Use:

   First you need to setup the git config. Do this by typing:

      > eazygit -n github-username -e github-email

   To Upload File in your repository just Follow This:

      With Commit Message (Note: Do not Use space)

         > eazygit -c filename -h commit-message -b github-repo-url

      With Default Commit Message

         > eazygit -c filename -z -b github-repo-url

   To Update:

      > eazygit -u OR eazygit --update
