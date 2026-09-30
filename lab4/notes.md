ans 1) global -- applies my username and password to all the repositories associated with account im currently working on. if 
global-- was not used then it would only apply the configurations to the current repository i was working on.

ans 2) Running ls -a reveals hidden files and directories (those starting with a dot .), including the .git directory.

ans 3) Git shows 4 untracked things in the terminal: `.venv/`, `README.md`, the current folder `./`, and `week2/`.
We shouldn't track `.venv/` because it's just a folder where Python downloads extra libraries to run on the computer.

ans4 ) After creating the .gitignore file and adding .venv/ to it, .venv/ completely disappears from the "Untracked files"
 list in git status.

ans 5) To keep the team on the same page. Committing `.gitignore` ensures everyone shares the same rules so nobody accidentally
 uploads `.venv/` or junk files into the shared project.

ans 6)After running `git add README.md`, the file moves from **"Untracked files"** to **"Changes to be committed"**.
In the Git three-stage model, `README.md` moved from the **Working Directory** into the **Staging Area** (also called the Index).

ans 7)The commit created hash 81267c0 on branch master, saving 5 files (.gitignore, README.md, lab4/notes.md, week2/lab01-log.txt, and week2/notes.md) with 247 insertions. In Git, the staged changes are now permanently saved into the local repository
 history as a commit snapshot. 

ans 8 )The first seven characters are called the **short commit hash** (or short SHA).
They act as a unique ID for that specific snapshot of the project, making it easy to identify, track, or revert to that 
exact commit in history without typing the full 40-character code.  

ans 9)1. Edit (modify or create files)
      2.Check status (git status to see changes)
      3.Stage (git add to prepare files)
      4.Commit (git commit to save the snapshot) 

ans10)README.md is placed in the root folder because hosting platforms like GitHub automatically render it on the project homepage. It acts as the front cover, giving anyone opening the repository an immediate overview of what the project is, 
who made it, and how to use it.

ans 11)gh auth login authenticates the session and securely saves an authentication token locally, configuring Git to use it automatically as a credential helper. This allows future pushes and pulls to authenticate seamlessly without prompting 
for a password each time. 

ans 12) The rendered content of the README.md file is showing on the repository front page.GitHub automatically renders this file because it is designed to act as the main documentation and entry point for the 
repository, giving visitors an instant overview of the project.   

ans 13)No, pushing does not change local history. git push only transfers local commits to the remote repository on GitHub—it leaves local commits, hashes, and commit log untouched. 

ans 14)A private repository is uploaded to GitHub's servers, saving all project history while restricting access to selected users like TAs.
A non-existent repository has no data hosted on GitHub at all, existing solely as local files on a personal computer. 
