### **Basic Git Commands**  

1. **Initialize a Git Repository**  
   ```bash
   git init
   ```
   Initializes a new Git repository in the current directory.  

2. **Clone a Repository**  
   ```bash
   git clone <repository_url>
   ```
   Creates a local copy of a remote repository.  

3. **Check Repository Status**  
   ```bash
   git status
   ```
   Displays the status of tracked and untracked files.  

4. **Stage Files for Commit**  
   ```bash
   git add <file_name>   # Add a specific file  
   git add .             # Add all changes  
   ```
   Moves changes to the staging area.  

5. **Commit Changes**  
   ```bash
   git commit -m "Commit message"
   ```
   Saves staged changes with a descriptive message.  

6. **View Commit History**  
   ```bash
   git log
   ```
   Shows a list of previous commits.  

7. **Check Differences in Files**  
   ```bash
   git diff
   ```
   Displays unstaged changes compared to the last commit.  

8. **Create a New Branch**  
   ```bash
   git branch <branch_name>
   ```
   Creates a new branch.  

9. **Switch Between Branches**  
   ```bash
   git checkout <branch_name>  
   # OR  
   git switch <branch_name>
   ```
   Moves to a different branch.  

10. **Merge a Branch**  
   ```bash
   git merge <branch_name>
   ```
   Merges the specified branch into the current branch.  

11. **Push Changes to Remote Repository**  
   ```bash
   git push origin <branch_name>
   ```
   Uploads local commits to a remote repository.  

12. **Pull Latest Changes from Remote**  
   ```bash
   git pull origin <branch_name>
   ```
   Fetches and merges changes from a remote branch into the local branch.  

13. **Delete a Branch**  
   ```bash
   git branch -d <branch_name>  # Delete local branch  
   git push origin --delete <branch_name>  # Delete remote branch  
   ```
   Removes a branch locally and from the remote repository.  

14. **Reset Changes**  
   ```bash
   git reset --hard <commit_id>
   ```
   Resets the repository to a specific commit, discarding all changes after it.  

15. **Revert a Commit**  
   ```bash
   git revert <commit_id>
   ```
   Creates a new commit that undoes the specified commit.  

16. **Check Remote Repository URLs**  
   ```bash
   git remote -v
   ```
   Lists the remote repositories linked to the local repository.  

17. **Stash Changes Temporarily**  
   ```bash
   git stash
   ```
   Saves uncommitted changes without committing them.  
