### **basic unix based terminal**
- `pwd` --> know current dir location
- `ls` --> list file
- `mkdir <folder_name>` --> create folder
- `mv <current_location> <target_location>` --> move current to target
- `touch <file_name>` --> create file
- `rm <file_name>` --> remove file
- `code .` --> shortcut to open vscode
- `wget <path>` --> to download
- `cd <to where>` move to some directory
    - `cd ..` move back 1 time
    - `cd ../..` move back 2 time
    - `cd folder1/folder2` move to folder2


### **git**
- git config --> setup config for your git
    - `git config --global user.name " your username"` --> setup global config your git username 
    - `git config --global user.email "your email"` --> setup global config your git email
- git init --> init local repository
- git add --> add your changes to staged 
state (ready to commit)
    - `git add .` --> add all modified / untracked file to staged
    - `git add <file_name>` --> add single file to staged
- git commit --> commit your staged file
    - `git commit -m "commit message"` --> commit using commit message
- git branch --> look at all branch at local repository
- git checkout --> change to other branch
    - `git checkout -b "branch_name"` create new branch
- git push --> push to remote repository
- git pull --> pull from remote repository to local repository

### **git outside ruangguru course outline (useful for work, try to explore it by yourself of course by googling)**
- git rebase
- git cherry-pick
- git stash
- git squash
- git tag
- semantic commit
- branch naming convention standard

### **etc to explore it by yourself**
- vi / nano editor
- `vi` --> open vi editor
- `nano` --> open nano editor