## Log File 

`git log` - lists all previous commits like this example:
```
commit 43433c674e3d6c86a889fad222dae179785893cf (HEAD -> master, origin/master, origin/HEAD) Author: Tim Taler   <mail@mail.com> Date:   Tue Apr 7 13:09:58 2020 +0100  Update index.html
```
One log entry contains
- The Secure Hash Algorithm (SHA) hash for the commit, which is used to uniquely identify each commit in a repository
- The Author and the corresponding email
- The date and time of the commit as well as 
- The commit message

A summery of the log can be called by `git shortlog`

### Options
- Filter by most recent commits, e.g. the three most recent ones `git log -n 3`
- Filter by date `git log --after="2021-10-2"` or git `log --before="yesterday"`
- Filter by file `git log -- main.py`
- Shorter output with `git log --oneline`
- Output all references (like branches and tags) `git log --decorate`
