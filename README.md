# Git Config
This is just a remote storage of my preferred `.gitconfig` aliases.

```
[alias]
	a = add .
	m = checkout master
	ci = commit
	cm = commit -m
	co = checkout
	br = branch
	st = status
	rem = rebase origin/master
	fix = commit --amend --no-edit
	wip = commit -a -m "WIP"
	piw = reset HEAD~1
	last = diff HEAD~1
	nuke = reset --hard HEAD
	fpush = push --force-with-lease
```
