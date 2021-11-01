# The git stash

The git stash can be used to temporarily put away all changes in the working directory.

By running `git stash`, all local modifications of files that are already tracked by git are put into the git stash.

You can mostly work with the stash like with any other commit (e.g., `git diff stash` or `git show stash`).

To retrieve the stash back onto your local working directory, issue the `git stash pop` or `git stash apply` command.
The first one will apply the changes to the working directory and then remove the stash entry, whereas the latter applies the changes and keeps the stash entry.

To drop the stash (e.g., after `git stash apply`) simply type `git stash drop`.

If there are any conflicts while `apply`ing or `pop`ing the stash, it will be kept for you automatically.
