# Principais comandos do git:

## Fluxo principal:

* git init
* git clone "url" .
* git status
* git add .
* git commit -a -m "message"
* git push
* git push -u origin (name)
* git push origin (name)
* git push origin --delete (name)
* git pull
* git mv (name) (new-name)
* git rm (name)

## Branchs e tags:

* git branch
* git branch -M main
* git branch -d (name)
* git checkout (name)
* git checkout -b (name)
* git tag 
* git tag -a (name) -m "message"
* git tag -d (name)
* git merge (name)
* git rebase (name)
* git rebase -i (name)
* git fetch

## Monitoramento e reset:

* git log
* git shortlog
* git reflog
* git show
* git show (name or hash)
* git diff
* git diff (name or hash)
* git restore (name)
* git reset --hard
* git reset --hard origin/name
* git reset --hard (hash)

## Remote:

* git remote -v
* git remote add origin "url"
* git remote rm origin

## Limpeza do repositório:

* git clean -f
* git gc
* git fsck

## Submódulo:

* git submodule
* git submodule add "url" .


