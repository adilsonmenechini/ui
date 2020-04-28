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

#### Criando um Branch Devolp
##### checkout 
```
git checkout -b Devolp
git status
git add .
git commit -m "crianção de branch Devolp "
git push origin Devolp
```

#### Migrando Branch Devolp para master 
##### Merge
```
git checkout master
git merge Devolp
git add .
git commit -m "Migração da branch Devolp para master "
git push origin master

```
