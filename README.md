# Git Config
This is just a remote storage of my preferred `.gitconfig` aliases.

```
[alias]
	a = add .
	m = checkout master
	ci = commit
	cm = commit -m
	ca = !git add . && git commit -m
	co = checkout
	br = branch
	st = status
	pu = push -u origin
	rem = !git fetch && git rebase origin/master
	ucl = git commit -am "[ci skip] Update CHANGES.md"
	fix = commit --amend --no-edit
	wip = commit -a -m "WIP"
	piw = reset HEAD~1
	last = diff HEAD~1
	plog = log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short
	nuke = !git add . && git reset --hard HEAD
	fpush = push --force-with-lease
```
