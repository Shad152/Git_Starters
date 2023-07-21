1. `git init` -> The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. Most other Git commands are not available outside of an initialized repository, so this is usually the first command you'll run in a new project.

2. `Working Area` -> The working area is where files that are not handled by git. These files are also referred to as "untracked files".It means that changes done or to be done in those files are not managed by git yet. 

3. `Staging Area` -> Staging area is files that are going to be a part of the next commit, which lets git know what changes in the file are going to occur for the next commit. This staging area is the place where git knows what changes will be done from last version to the next version.

4. `Repository Area` -> This area actually contains the details of all previous registered version and the files in this area, git already manages them and knows their version history.

5. `git add <file>` -> moves file from working area to the staging area.

6. `git rm --cached <file>` -> moves file back from staging to working area.

7. `commit` -> Commit is particular version of a project. It captures a snapshot of the project's staged changes and create a version out of it.

8. `git commit` -> git commit is used to create a snapshot of the staged changes along a timeline of a Git projects history.

9. `git log` -> list downs all the commits of the repository.

10. `git restore` -> The "restore" command helps to unstage or even discard uncommitted local changes. On the one hand, the command can be used to undo the effects of git add and unstage changes you have previously added to the Staging Area.

11. `git restore --staged` -> With the --staged option, however, the file will only be removed from the Staging Area - but its actual modifications will remain untouched.

12. `Diff between git rm and git restore` -> If you want to move the whole file back to the untracked state, then we do git rm, otherwise if we just want the changes to be moved in working or staging area then we do git restore.

13. `git diff commit1 commit2` -> gives the difference of all file changes between two commits.

14. `git commit -m "<your commit message>"` -> If we want to avoid opening the prompt to add commit message we can use this command

15. `git remote` -> This commands helps you to connect one repository to any another repository. As a command it will list down all the remote connection

16. Remote Connection -> It helps you to link two git repositories for uploading and downloading changes from each other.

17. `git remote add <name of remote> <link of remote>` -> This command helps us to create a remote connection to the link of remote with name mentioned in command. The default name is origin

18. `git remote rm <name of remote>` -> This command deletes the remote connection with remote name mentioned in this command.

19. `git remote rename <oldname> <newname>` -> This command renames the remote connection.

20. `git add .` -> This command will add all files from working area to staging area.

21. `git pull <remote name> <branch name>` -> download the latest changes from the branch of the mentioned remote to your local repo.

22. `Stash` -> stash is a feature that allows you to temporarily save your changes in a "stash" without committing them.The stash essentially allows you to store your modifications separately, so you can return to them later.

23. `git stash` -> When you have made some modifications to your working directory, but you're not ready to commit them yet, you can use the `git stash` command.

24. `git stash apply` -> will bring back the last stash that you have stashed. This command applies the changes from a stash to your working directory. By default, it applies the most recent stash.

22. `Stash` -> stash is a feature that allows you to temporarily save your changes in a "stash" without committing them.The stash essentially allows you to store your modifications separately, so you can return to them later.

23. `git stash` -> When you have made some modifications to your working directory, but you're not ready to commit them yet, you can use the `git stash` command.

24. `git stash apply` -> will bring back the last stash that you have stashed. This command applies the changes from a stash to your working directory. By default, it applies the most recent stash.

25. `git stash --include-untracked -- <filename>`-> This command will stash all the changes in both tracked and untracked files, effectively saving your modifications in the stash while leaving your working directory clean.

26. `git stash save "Your stash message" --include-untracked` -> If you want to add your own stash message for better understanding of what stash you did in a particular stashing.

27. `git commit --amend`-> It add the current changes to commited in previous commit, it make the commit history look clean.