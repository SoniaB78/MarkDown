# Programme Ecole du Web
Ce repository à plusieurs vocations:
1. Il permet de mettre en pratique les petits tips donnés pour faire vos recherches.
2. En apprendre plus sur une des notion qui apparaît dans le programme.
3. D'apprendre à mettre en forme un document avec le Markdown.
4. Mais surtout il fait utiliser Git, mutualiser le travail est l'objectif final de cet exercice.  

Les étapes décrites dans la marche à suivre ne sont qu'un résumé, suivez les étapes du lien.

## Marche à suivre
En vous appuyant sur les [étapes présentes sur cette documentation](http://thelia-school.com/faire-une-pull-request-sur-un-projet-thelia/faire-une-pull-request.html). 

Créer sur vos comptes personnels GitHub un Fork depuis ce repo GitHub :
[Lien vers le repository sur lequel il faut faire un fork](https://github.com/SoniaB78/recherche-en-markdown-avec-git).  

__Forkez__ le repository recherches-en-markdown, __clonez__ le pour l'avoir en local (nécessite de créer un dossier vide dans lequel on fait un git init), créez votre __branch__ pour travailler dessus.

Ajoutez l'origine à votre repository avec __remote__  (*git remote add upstream url*).  

Tenez __TOUJOURS__ votre branch master à jour avec les modifications qui arriverons au fûr et à mesure avec un __git pull__ (*git pull --ff-only upstream master*).  

Une fois votre environnement de travail installé, __faite vos recherches__ sur le langage choisi, [mettez en forme](https://openclassrooms.com/fr/courses/1304236-redigez-en-markdown) votre partie du document de manière cohérente avec le reste de la mise en page.  

Travaillez sur votre partie en sauvegardant en __local__ avec *git add .* et *git commit -m "commit message"* mais __je répète__ ne faites pas de push sans avoir fait le git pull --ff... au préalable.   

Vous devrez __lier votre branch__ à votre branch master (*git rebase master*) et __push sur votre branch__.  
Vous pourrez ensuite faire une demande à l'auteur original du repository pour qu'il pull vos modifications(*pull request*).  

## Organisation du document
J'ai créé un fichier en markdown, vous choisirez __une__ notion chacun dans la liste ci-dessous et reporterez les résultats de vos recherches dans le fichier recherches .md :
- git
- html
- css
- javascript
- jquery
- bootstrap
- ajax
- php
- programmation orientée objet (poo)
- sql
- markdown
- wordpress  

Vous respecterez l'ordre des éléments de la liste pour ajouter votre contenu au fichier, ainsi la personne ayant choisie git ne mofifiera que le premier lien du sommaire et la première section.

## Problèmes courants
Il arrive trop souvent que la pull request mène à un conflit, vérifiez que vous ajoutez le contenu au bon endroit sans rien modifier ailleurs.  
En effet le processus d'assemblage repose sur une gestion précise du travail en collaboration.  
Aussi et pire encore l'acceptation d'un pull request fait à partir d'un repository qui ne s'est pas tenu à jour sur l'avancée du projet peut supprimer du contenu.  


## Documentation supplémentaire
[Exemple de repository](https://github.com/Ma6Tvacoder-Docs/partages/blob/master/supports/techno_back.md)  
[Différence entre fork et clone](https://www.toolsqa.com/git/difference-between-git-clone-and-git-fork/)  
[Autre marche à suivre pour faire un fork](https://www.christopheducamp.com/2013/12/16/forker-un-repo-github/)  
