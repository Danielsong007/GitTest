- !!Note: create an empty Repo from website firstly, and then clone it. (or you cannot synchronize main branch.)
- Install git
    - sudo apt-get install git
    - git config --global user.name "user_name"
    - git config --global user.email "email_id"
- For a specific folder
    - git init
    - git add sample.py README
    - git commit -m 'hhhhhh'
    - git remote add origin (here use: ssh link in github)
    - git push origin master
- Branchs
    - git branch -a // list all
    - git branch (local branch name) // create local branch
    - git branch -d (local branch name) // delete local branch
    - git branch checkout (local branch name) // change local branch
    - git push origin (remote branch name) // push local branch to remote
    - git push origin :(remote branch name) //delete remote branch


k