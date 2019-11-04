# Git Commands

### Create new Repository and initilize it 
 1. **Login your github account**
    - **Go to repositories tab**
    - **then click new button**
    - **enter repository name**
    - **then hit Create repository button**

   *copy that https- https://github.com/username/repo_name.git*

 2. **create a directory on your PC**
    - **then open the directory in terminal**
    - **type following commands:**
     ```
         $ git init
         $ echo "# Title" >> README.md
         $ git add README.md
         $ git commit -m " type message here "
         $ git remote add origin <paste that copied address>
         $ git push origin master
     ```


### Clone repository
    `git clone <url>`


### Create new branch 
    `git branch <branch-name>`


### Delete branch
    `git branch -D <branch-name>`


### Switch to new branch 
    `git checkout <branch-name>`


### History of branch
    `git log`












































