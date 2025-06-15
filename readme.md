# Python
[Cours Scripting sous Linux https://www.eni-training.com/portal/client/mediabook/home ]

This repo is used as a starter for learning scripting python in Linux.


## I- Chapter 1 : Setup and Configuring Git

      1- Create an account here
      2- Installation Git on Debian
            $ apt install git-all 
            
      3- Configuration Git
            $ git config --global user.name "RiantsoaRakotovao"
            $ git config --global user.email " riantsoa28@gmail.com"
            $ git config --global core.editor "/usr/bin/nano"

            The purpose of these commands are to identify who commit and to use nano default.

            To see the configuration of the 3 commands
            $ git config --list
            
      4- Configuration Git with SSH
            Step 1 : Create a pair of SSH key with passphrase 
            $ ssh-keygen -t ed25519 -C "riantsoa28@gmail.com"
            - save the file ssh and the passphrase

            Step 2 : Copy the public key in Github
            - < Project < Settings < Deploy Key <  Add deploy key
            - Put the same name as the filename of public and copy the contains

            Step 3 : Test the access SSH 
            $ ssh -vT git@github.com
            Comment : Github doesn't provide the shell acces
      
            

      5- Create a project
      6- 
      
