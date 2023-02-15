# bigdata

## cloner un projet

`git clone <nom du projet>`

## initialiser un projet

`git init`

## checker les modificartions apportées au projet

`git status`

## suivre un fichier

`git add <nom du fichier>, <fichier 2>`

## suivre tout les fichiers 

`git add .`

## sauvegarder en local 

`git commit -m "<message>"`

## envoyer ma version au repo distant

`git push origin main`

## Empêcher la sauvegarde de certains fichiers

-   A la  racine de votre projet, créez un fichier `.gitignore` qui contiendra le chemin des fichiers à ignorer

# En cas de conflit sur un même fichier

vous avez dans votre fichier un exemple de ceci :

```
<<<<<<< HEAD
quentin = "blabla"
=======
quentin = "Je suis passé par là"
cyriak = "j'ai modifié ton fichier"
>>>>>>> 1fc9ae27935fae126e63d8b8fbb04e3eaa9b3d72
```

HEAD : Ce qui est sur votre machine

===== >>>> : Ce qui provient du repo distant

Vous avez 3 choix possibles : 
- conserver ce qui est sur votre machine
- conserver ce qui provient du repos distant
- conserver les deux

Une fois le choix fait, enregistrez les changements et push le tout