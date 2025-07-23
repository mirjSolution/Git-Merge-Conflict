# 🛠️ Git Merge Conflict

This project demonstrates how merge conflicts occur when two developers make changes to the same line of code in a file, and how to resolve them.

## 📄 Scenario Summary

![Merge Conflict](Images/mergeconflict.gif)

1. 👨‍💻 Developer 1 makes a local change to `test1.txt` and commits it.
2. 🌐 Developer 2 edits the same file commits to the remote repository.
3. 🚫 When Developer A tries to push, Git rejects it due to conflicts.
4. ⚠️ A `git pull --rebase` is attempted, and a merge conflict occurs.
5. 🧩 The conflict must be manually resolved.
6. ✅ After resolving, run `git rebase --continue` to complete the rebase.
7. 🚀 Finally, push changes successfully.

## 📝 Conflict Resolution Steps

```bash
git status                      # Check the conflict status
# Edit the conflicted file to resolve manually
git add <file>                 # Mark the conflict as resolved
git rebase --continue          # Continue the rebase
git push                       # Push the final changes
```

🧑‍💻 _Created by Rico John Dato-on_
🔗 [LinkedIn](https://www.linkedin.com/in/rico-john-dato-on) • [Portfolio](https://ricodatoon.netlify.app)
