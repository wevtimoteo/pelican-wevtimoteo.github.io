Deploy to Github Pages:
```
$ pelican content -o output -s pelicanconf.py
$ ghp-import output
$ git push origin gh-pages:master
```
