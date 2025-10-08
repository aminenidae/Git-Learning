Lesson 1 — “From Local Setup to First Push”

| 🧩 Step                   | 💻 Command                                         | 🗒️ Explanation                                                                                          |
| ------------------------- | -------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| 1️⃣ Install Git           | *(done before class)*                              | Git is the version control tool that tracks your changes.                                                |
| 2️⃣ Configure username    | `git config --global user.name "Your Name"`        | Tells Git who you are — appears in your commit history.                                                  |
| 3️⃣ Configure email       | `git config --global user.email "you@example.com"` | Your Git identity (should match your GitHub email).                                                      |
| 4️⃣ Initialize repository | `git init`                                         | Turns the current folder into a Git repository (creates a hidden `.git` folder).                         |
| 5️⃣ Check status          | `git status`                                       | Shows what’s changed, what’s staged, and what’s untracked.                                               |
| 6️⃣ Add files             | `git add .`                                        | Stages all files in the current folder for committing. (Use `git add <filename>` to add a specific one.) |
| 7️⃣ Commit changes        | `git commit -m "Your message"`                     | Takes a *snapshot* of the staged files — saves them in history.                                          |
| 8️⃣ View history          | `git log`                                          | Lists all commits (with ID, author, date, and message).                                                  |
| 9️⃣ Connect remote        | `git remote add origin <repo-URL>`                 | Links your local repo to a GitHub repository.                                                            |
| 🔟 Verify remote          | `git remote -v`                                    | Confirms the link between local and remote.                                                              |
| 11️⃣ Push to GitHub       | `git push -u origin main`                          | Uploads commits to GitHub and sets up the connection for future pushes.                                  |

Bonus Practice Tips

Try these mini-drills for practice:

After editing a file → git status, git add ., git commit -m "Updated file", git push

Run git log --oneline to see a compact list of commits.

Run git help <command> for built-in explanations (e.g. git help commit).

_____________________________________________________________________________________
🧭 Lesson 2 Summary — Branching & Merging in Git
#	Command	Meaning	Description
1	git branch	view branches	Lists all branches in your repo. The active one has a * next to it.
2	git branch <branch-name>	create branch	Makes a new branch but doesn’t switch to it.
3	git checkout <branch-name>	switch branch	Moves you to another branch.
4	git checkout -b <branch-name>	create & switch	Shortcut to create and immediately switch to a new branch.
5	git add <file>	stage file	Prepares the file to be committed (tracked for next snapshot).
6	git commit -m "message"	save snapshot	Saves staged changes with a description message.
7	git merge <branch-name>	merge branch	Combines changes from the specified branch into the current one.
8	git branch -d <branch-name>	delete branch	Safely deletes a branch that has already been merged.
9	git log --oneline --graph --all	view history graph	Displays all commits and branches in a visual tree.
10	git pull origin main	sync from GitHub	Downloads (fetch + merge) updates from your GitHub repository.
💡 Concepts You Mastered

A branch is a separate workspace for experimenting safely.

Merging integrates changes into the main project.

Deleting branches keeps your repo clean after merging.

Pulling syncs your local files with GitHub’s remote version.
