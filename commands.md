             Repository Initialization
             
git init                     # Initialize a new Git repository
git clone <url>              # Clone an existing repository

                Staging & Committing
                
 git status                   # Show changes
git add <file>               # Stage a file
git add .                    # Stage all changes
git commit -m "Message"      # Commit staged changes

              Branching & Merging

git branch                   # List branches
git branch <name>            # Create new branch
git checkout <name>          # Switch to branch
git checkout -b <name>       # Create & switch to new branch
git merge <branch>           # Merge a branch into current

             Pushing & Pulling

git remote add origin <url>  # Add a remote
git push -u origin main      # Push to remote (first time)
git push                     # Push committed changes
git pull                     # Pull latest changes
      
            🧹 Undoing Changes

git reset <file>             # Unstage file
git checkout -- <file>       # Discard changes in file
git revert <commit>          # Revert a commit
git reset --hard <commit>    # Reset history and working directory (⚠️ destructive)

              🔍 Viewing History

git log                      # View commit history
git log --oneline            # One-line format
git diff                     # Show unstaged changes
git show <commit>            # Show details about a commit
