## Top 15 Git Commands every Developers Should know

## Top 15 Git Commands every Developers Should know

If you are new to Git & GitHub, This blog is gonna be greatly helpful for you as I am going to explain all the commands that you should know.

**So, Let's Git Started:**

## 1. git init

This Command is used to initialize a project as an empty git repository.

## 2. git remote add origin

This command is used to connect a project to a remote repository.

`git remote add origin https://github.com/Debajyoti14/Quiz-app.git`

## 3. git remote

This Command is used to show connected remote repository.

## 4. git add
This command is used to stage all untracked and modified files. git add . to stage all unstaged & modified files.

`git add index.html`

## 5. git status

This Command is used to show the status of your files in the repository like- untracked, modified, etc.

## 6. git commit

This Command is used to commit the staged file and also allows you to write a commit message for referring.

`git commit -m "names.txt file is added"`

## 7. git push -u origin

This Command is used to push committed files to the remote repository and also in the specified branch. This -u tag is needed for the first time pushing the file to the remote repository. Then you only need to write **git push origin/upstream branch name**. Use upstream if you want to push in someone's repository.

`git push origin main`

## 8. git reset

This Command is used to unstage commits. You can also add the commit id after **git reset** to unstage the specific commit.
Always use the below commit id which you want to delete.

`git reset <commit-id>`

## 9. git pull

This Command is used to pull the updated codebase to your local repository.

`git pull origin main`

## 10. git branch

This Command is used to show the current branch.

## 11. git checkout -b branch-name

This Command is used to create and move to the branch instantly.

## 12. git checkout branch-name

This Command is used to move between branches.

## 13. git branch -a

This Command is used to show all the branches in your local repository.

![Screenshot 2022-02-28 161426.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1646045076819/SZk9xTMWe.png)

## 14. git fetch

This command is used to fetch the most updated version of your remote repository to your local repository.

## 15. git stash

Git stash saves the uncommitted changes locally, allowing you to make changes, switch branches, and perform other Git operations.

Thank you for reading! If you think I have missed some other important git commands which you often use, please let me know!