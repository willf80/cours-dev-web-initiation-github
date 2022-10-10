# Introduction à GIT

## Installation de GIT

https://git-scm.com/downloads

## Initialisation du projet

```bash
git init
```

## Premier commit

```bash
git add . #ajouter tous les modifications de fichier à git

git commit -m "mon premier commit"
```

Faire le lien avec le dépot distant
Pour obtenir le lien origin, il faut créer un repository sur github.com
```bash
git remote add origin https://...
```

Envoyer le commit local vers le dépôt distant github
```bash
git push -u origin master
```
