### Base git

`init` : Permet d'initialiser un depot git local dans le repertoire courrant. Cela se traduit par la presence d'un dossier cache `.git/` a la racone du depot.
L'édition ou l'ajout de fichier dans ce repo sera detecteé par Git, pour le viualiser dans le terminal on utilise la commande :  
```
Git init
```

Le depot git ou repository est le dossier qui contient les données que l'on sougaite versionner. On y trouve un dossier cache `.git./`.

Pour vérifier l'état du dépot git, utiliser la commande :
```
git status
```

Renommer la branche principale :
```
git branch -m "nom_de_la_branch"
```

Avant de sauvegarder les modifications, il faut ajouter les modifications que l'on souhaite sauvegarder avec la commande :
```
git add "nom du fichier"
```

`Commit` : Changement d'un fichire suivie par git  

La sauvegarde s"effectue ensuite avec la commande :
```
git commit -m "message de commit"
```
