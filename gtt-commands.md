# For. New. Projects
1. Git initialization
```
    git init
```
2. Add **Files** and **Folder** to git for tracking
```
    git add .
```
Note: . is for all files and folder, in place of . we can add file name.
3. After completing: save all codes as some version
```
git commit -m "[Your_commit_message]"
eg: git command -m "project initilized"
```
4. optional step: chaning main branch
Note: defult branch is alwaus "master"
    ```
    git branch -M "[your_main_branch_name]"
    ```
5. Add remote repo link or repository url
    ```
    git remote add origin "[your_repository-url]"
    ```
6. Push the recent commited code to remote
    ```
    git push -u origin "[your_current_branch_name]"
    ```
    Later (id one push is already done using -u: upstream)
    ```
    git push

 (*)for italic
 (**) for bold
 (`) highlight

 7. To preview the current git status
 ```
    git status
```
8. To check linked remote url
```
    git remote -v
```
9. To update the remote repo url
``` 
   git remote set-url orihin [your_repo_url]
   To verify/Display added remote url:
   git remote -v
```
10. To config the user.name and user.email:
```
    Project Based config:
    git config user.name [your_github_username]
    git config uder.email [your_guthub_email]

    Global config:
    git config --global user.name [your_github_username]
    git config --global user.email [your_github_email]

    To verify/Display config (Note: enter to view more config and q to exit the opened editior):
    git config --list
```
# After changing on project
1. git add .
2. git commit -m "[your_commit_message]"
3. git push
# using personal account Token (PAT) on https url:
 https://[PAT]@github.com/[github_username]/[Project_name]

To update remote url:
