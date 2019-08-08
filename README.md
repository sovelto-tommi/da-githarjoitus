# da-githarjoitus

## Harjoitus 5
Harjoitukset 3 ja 4 <em>soveltuvin osin</em>
* `git init`
* `vim .gitignore`
* `git add .`
* `git commit -m"Projektin pohja, eli .gitignore"`
* `vim main.py` 

Github: projektin luonti, luo myös README.md
* `git remote add origin https://github.com/....`
* `git pull origin master --allow-unrelated-histories`
    * tai `git fetch`... ja `git merge`...
* `git push origin master`

Nyt pitäisi olla seuraava tilanne

```
$ git status
On branch master
nothing to commit, working tree clean
```

Voi vielä varmistaa että muutokset siellä:
```
$ git ls-files
.gitignore
README.md
main.py
```` 

