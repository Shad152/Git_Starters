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