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
9. 