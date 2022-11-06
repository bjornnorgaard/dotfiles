# Git Aliases

```shell
[alias]
	l = log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
	a = add --all
	d = diffP
	s = status
	b = branch -a
	f = fetch -p
	bd = branch -d
	bdd = branch -D
	ca = commit -am
	cm = commit -m
	rh = reset --hard
	ph = push origin head
	pm = pull origin main
	co = checkout
	com = checkout main
```