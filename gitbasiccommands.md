Git Commands Cheat Sheet

This is a notebook-ready compilation of Git commands useful for your photography site workflow.

⸻

1. Check Repository Status

git status

   •  Shows the current state of the working directory and staging area.
   •  Lists modified, new, and deleted files.

2. Stage Changes

git add <file>
git add .

   •  git add <file> stages a specific file.
   •  git add . stages all changes (new, modified, deleted) in the repo.

3. Commit Changes

git commit -am "Your message here"

   •  Records staged changes into the local repository.
   •  The message should describe what was changed and why.

4. Push to Remote

git push origin main 

   •  Uploads local commits to the remote repository.
   •  <branch> is usually main, master, or gh-pages.

git push origin main --force 

   •  Uploads local commits to the remote repository.
   •  <branch> is usually main, master, or gh-pages.


extra commands:

7. Undo Local Changes

git checkout -- <file>

   •  Reverts unsaved changes in a file back to the last committed version.

8. View Commit History

git log --oneline

   •  Shows commit history in a compact form (one line per commit).

9. Create a New Branch

git branch <branch-name>

   •  Creates a new branch without switching to it.

10. Switch Branch

git checkout <branch-name>

   •  Switches to the specified branch.

11. Create and Switch to Branch

git checkout -b <branch-name>

   •  Creates a new branch and switches to it immediately.

12. Merge Branch

git merge <branch-name>

   •  Merges the specified branch into the current branch.

13. Pull Latest Changes

git pull origin <branch>

   •  Fetches and merges changes from the remote repository into your local branch.

14. Remove a File from Tracking

git rm <file>

   •  Removes a file from the repository and stages the deletion.

15. Rename a File

git mv <oldname> <newname>

   •  Renames a file and stages the change.

16. Discard All Local Changes

git reset --hard

   •  Resets the working directory to the last commit, discarding all changes.

17. Clone a Repository

git clone <repo-url>

   •  Creates a local copy of a remote repository.

18. View Differences

git diff

   •  Shows differences between working directory and staging area.

19. View Differences Staged vs Committed

git diff --staged

   •  Shows differences between staged files and last commit.

20. Tag a Commit

git tag <tag-name>

   •  Adds a tag to the current commit for release or version tracking.

⸻

💡 Workflow Example:

1. git status       → Check changes
2. git add .        → Stage changes
3. git commit -m "Message" → Commit
4. git push origin main → Push to remote