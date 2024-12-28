# Hello
Description

## Free Code Camp Tutorial 

### cloning
1. git clone (https or ssh)   ---> (cloning the repo)


### Creating repo
2. git init                   --->(Initilizes git folder for saving changes)
3. git add (./ or filename)     --> Adding file 
4. git commit -m "message" - m "desc"     ----> commiting the added file and only saved locally
5. git push origin master                    ---> push the commited file to branch


### STatus
6. git status    ---> it provides modified or untracked or deleted files which don't know to the git folder

### Connect repo to the project available on local
7. git remote add origin (ssh repo link.git)

### Removing already connected github repo
8. git remote remove origin

### Check Connected repo
9. git remote -v

### Using upstream to push files to github
10. git push -u origin main  (Next if we use git push it pushes default to origin/main)

### Branching
11. git branch ---> To see all available branches in current repo
12. git checkout -b (branch-name)   ----> To create new branch
13. git checkout (branch-name)     -----> Switch between branches
14. git branch -d (branch-nae)     ---> delete the branch

Create the branch and make changes and push to the branch.
Then the Mentor sees the PR(Pull Request) and review the code and make merging
15. git pull origin (branch-name)    --->  takes the merged code from remote to local machine