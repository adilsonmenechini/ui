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
 git checkout -b gh-pages
 git push origin gh-pages

 git status && git add . && git commit -m "update _config.yml" && git push -u origin gh-page
```
