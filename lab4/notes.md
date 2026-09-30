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

ans 7)  
