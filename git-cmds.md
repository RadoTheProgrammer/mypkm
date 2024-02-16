# Git commands

```
git config --global user.name "RRTheProgrammer"
git config --global user.email "rado@arazakar.com"
git config --global init.defaultBranch main
git config -h / git help config


git init
git status
git add index.html
git rm --cached index.html
git add .
git commit -m "first commit"
git diff
git restore --staged index.html
git commit -a -m "updated text"
git restore scratch.png
git mv index.html main.html
git commit -m "channnggggged the filename of index.html"
git log --oneline
git log -p
git reset 9a1fb89
git rebase -i --root
git branch FixTemp
git branch
git switch FixTemp
git merge -m "Merge fix" FixTemp
git branch -d FixTemp
git switch -c UpdateText
git commit -a -m "update index index"
if you have bug:
    create a branch
    make change in branch
    merge back to the main branch
git remote add origin https://github.com/RadoTheProgrammer/mywebpage-test.git
git branch -M main
git push -u origin main
git push --all
git fetch
git merge
git pull (= git fetch + git merge)


```

# Sources

* [video git](https://www.youtube.com/watch?v=tRZGeaHPoaw)
