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
