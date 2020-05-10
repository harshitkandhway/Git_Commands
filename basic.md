# Method 1 (Github -> add repository-> clone -> creates folder in file structure ->all project work is done inside this folder)
- Features already present
1) remote already set
2) no need to inititalise git by git init
3) upstream is also set by default to master

Steps :
1) Login to github and create a repository
2) copy the repository url from clone and download button
3) Open your folder structure in your system and open git bash
4) Run the clone command : git clone <paste_repository_url>
5) Open the folder and work inside it(4 files developed)
6) OPen git bash command prompt
7) Run git commands as follows :
 - git status ( unsaved,saved,modified,deleted,new_add)
 - git add . (this will add all the files in the local repository) || - git add <filename> (multiple files can be added with space between file name)
 - git commit -m "message for commit" (-m is used for messaging)
 - git push origin master ( All the changes from local master will be pushed to the master in the remote(github repository)).
 
# Method 2 (Github -> add repository , file structure->folder in which project exists)
- Extra steps to be followed
1) git init (intialize the folder in which a project already exist to a git repository)
2) Link the remote repository to the local repository
 - git remote add origin <url_of _the_repository_from_clone_and_download_link>
 - git remote -v -> List all remotes added to the local
 
 Common steps:
3) Open git bash command prompt
4) Run git commands as follows :
 - git status ( unsaved,saved,modified,deleted,new_add)
 - git add . (this will add all the files in the local repository) || - git add <filename> (multiple files can be added with space between file name)
 - git commit -m "message for commit" (-m is used for messaging)
 - git push origin master ( All the changes from local master will be pushed to the master in the remote(github repository)).
 
