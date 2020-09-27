# Git_Commands

Useful commands

1)When some files from local repository is deleted and committed and we want it back from remote repository with git pull, it will say already updated for that we need to run the command below before we take a pull.
# git reset --hard origin/master

2)When some files from local file system is deleted but not committed and we want it back.
# git checkout .            (remember to a dot for all files or specific file name for single file insertion)

3)We can also use the command below to take a pull from a remote repository
# git pull new_origin master --allow-unrelated-histories 

4)To check status of branch of local repository to that of remote repository we need to execute 
# git checkout

5)To check whether a SSH key is successfully linked to github account(If this shows hi profile_name , ssh_key is successfully linked)
# ssh -T git@github.com

6)To check list of git remotes
# git remote -v

7)To create SSH Key in the system
# ssh-keygen -t rsa

8)to change permission of a file named mvnw
# git update-index --chmod=+x mvnw

9)To find user settings for local machine
# git config -l

10) To unstage a file which was previously added using (git add .)
git restore --staged 1.txt
