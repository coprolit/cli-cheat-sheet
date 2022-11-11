# CLI commands cheat sheet
Useful CLI commands

### Directories
```
pwd                       # Print working (current) directory path
ls                        # List directories
ls -a                     # List directories including hidden
cd foo                    # Go to foo sub-directory
cd ..                     # Go to parent directory
cd                        # Go to home directory
cd -                      # Go to last directory

mkdir foo                 # Create a directory
rm -r foo                 # Delete directory including contents
```

### Files
```
touch foo.txt             # Create file or update existing files modified timestamp
rm foo.txt                # Delete file
open foo.txt              # Open file in the default editor
cp foo.txt /documents     # Copy-paste file to a folder
```

### Processes
```
ctrl+c                    # Exit the current process the terminal is running
```

### Git
```
git init                  # Create a new local repository
git add file.ts           # Add specific file to staging
git add .                 # Add all changed files
git commit -m 'This is a test commit'
git status                # List current branch and any changes to commit

git branch                # Lists branches on current repo and the current branch
git branch newBranch      # Create branch
git remote -v             # List the current remote repository
git rebase master         # Move the entirety of the current branch on top of master
git merge origin/master && git reset --soft origin/master 
                          # Reset current branch on master & squash all commits on branch
git merge newBranch       # Merge the branch you're currently in with another. Keep in mind the changes will be incorporated only to the branch you're currently in, not to the other one
```

### Node modules
npm cache clean --force   # clear local npm cache folder

### SSH
```
ssh hostname                 # Connect to hostname using your current user name over the default SSH port 22
ssh ssh://user@hostname:8765 # Connect to hostname using the user over a custom port
```

### Vim
```
:q                        # Exit the editor
:q!                       # Quit with unsaved changes
:wq                       # Save and exit
:wq!                      # Override read-only permission
:w newfile                # Save the text to newfile
```
