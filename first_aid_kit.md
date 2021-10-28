# Your git first-aid kit

## when was the bug introduced?
'git blame' see code and commit messages: when did who what?
'git diff branch_1..branch_2' the changes between two different branches. *Tip:* you don't have to copy the whole hashes, only the unique part of them.

## restore older version
'git reset [--soft/--hard] HEAD~[n]' reset the repository to the n-th prior state, with the changes stored --soft' or with the changes thrown away '--hard''
'git revert' make minus delta

## Error: a merge conflict!
Use 'git rebase' to preserve a linear history. 'git merge' is strongly discouraged.