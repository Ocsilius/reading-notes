## Terms

### Git
 - A *version control* system.
- Allows collaboration.
- Keeps all files in one repository, being able to keep a history of changes with associated viewing, application, and removal of the changes.
- Has a special label ***HEAD*** = *"You are here."*
- *Command line Tool*

### Github
- Different than **Git**.
  - A cloud-based version.
  - A sharing system for collaboration between coding.
  - It uses Git to help manage the team's work: Version tracking, Reviewing Changes, Keep changes separate until you want to add them in.
  - Allows code to be rolled back/changed/tested prior to implementation.
  - Can work on code offline and push online later, or vice-versa.

### Gitflow:ACP
- ACP = *Add/Commit/Push*

### Repository
- A *collection of files* for a project.
  - Includes the structure and content in the same collection.


### Version control
- Prevents multiple types of the same file (i.e. termpaper.docx; termpaper2.docx; etc.).

### Commits
- Represent each version of files or set of files.

### Git Clone
1. Git Clone of an existing Git repository from a server with the repository's URL Format *$ git clone https://github.com/test*
1. Use the repository into a directory with another name of your choosing Format *$ git clone https://github.com/test mydirectory*

### Git Commands
| Command | Use | Example |
| ---     | --- | ---     |
| `git config` | Settings for Git such as *user.name* and *user.email* ; Also can check settings with `git config --list` | *git config --global user.name "John Doe" |
| `git init` | Creates a subdirectory in location   | *git init* - Creates a .git subdirectory with repository files. |
| `git clone` | |
| `git add` | Adds designated files for git to track  | *git add ``*.c``
| `git commit` | Changes are committed locally but not to remote  | *git commit -m "Corrected repository Table of Contents" // *git commit -a* - Commits all files |
| `git diff` | Shows differences in file before merging | *git diff <source> <target> |
| `git reset` | Undoes the local changes and commits  | *git fetch origin // git reset --hard origin/master  (pulls from server and removes the newer changes) |
| `git status` | Shows files changed and not yet committed | *git status*
| `git rm` | Removes a remote | *git remote rm jane*
| `git log` | Shows current ID, used to find a unique changeset ID  | *git log* |
| `git show` | Shows tag and commit  | *git show v2.0*
| `git tag` | Marks an update   | *git tag 1.0.0 <commitID> |
| `git branch` | Creates a new branch when paired with the new name | *git branch test* |
| `git checkout` | Switches to another branch  | *git checkout test*
| `git merge` | Merges changes from one branch into your current one. | // |
| `git remote` | Used to view the short names of all specified remote handles (with *git remote -v* you can view all remote URLs with their remote names) | *git remote -v* |
| `git push` | Pushes changes "upstream" | *git push [remote-name][branch-name]* |
| `git pull` | Use in the working directory to fetch and merge remote changes | *git pull* |
| `git stash` | Temporarily removes changes and hides them for a clean working directory. To undo use *git stash apply*  | *git stash* |
| `git help` | Get more info on a command - Format of *git help* ***command*** | *git help init* |


## Navigating the Terminal

1. ls -a = *shows all files in your location*
1. pwd = *Shows current location*
1. Git remote -v *shows what is out on the cloud and locally on the machine*
