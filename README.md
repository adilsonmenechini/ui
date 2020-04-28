# Projeto Blog


## Docker Jekyll

```
docker run -it -v $(pwd):/srv/jekyll -w /srv/jekyll jekyll/minimal sh

```

### Permalink
_config.yml

```
permalink: /:categories/:year/:month/:day/:title:output_ext
```

### Git
_config.yml

```
<<<<<<< HEAD
 git checkout -b gh-pages
 git push origin gh-pages

```
=======
git checkout -b Devolp
git status
git add .
git commit -m "COMENTARIO 1 "
git push origin Devolp
git checkout master
git merge Devolp
git add .
git commit -m "COMENTARIO 2 "
git push origin master

```
>>>>>>> Devolp
