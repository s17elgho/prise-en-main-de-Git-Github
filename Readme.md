## Créer un repo github à partir d'un répo local:  
Avant de commencer, il faut installer git et créer un compte sur github (choisir même adresse mail et nom d'utilisateur)
1/ créer un repo vide sur github  
2/ cloner ce rep sur la machine locale en utilisant :  
git clone lien https du repo  
3/ mettre les fichiers voulus dans le repo local   
4/se placer dans un terminal  ouvert dans le repo local et taper les commandes  
git init (créer un dépôt git initialement vide)  
git add . (ajouter tous les fichiers à l'index)  
*git status* (permet de comparer la version git et la version locale)  
*git log* : historique des commit  
git push origin master ( pour pusher tout sur github )   

## Modifier depuis ma machine locale un repo déjà existant sur github   
Modifier d'abord ce qui est à modifier et ensuite ouvrir un terminal dans le repo local  et taper:  
1/ git add 'nom du fichier' s'il n'est pas dans l'index  
2/git commit -m 'description de la modification'
3/git push origin master   

## Modifier depuis github un repo local :  
Se placer dans le repo et utiliser la commande
git pull origin master
