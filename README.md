how to change `master` to `main` in local machine:

```
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```
