Exercice GIT base manip 
 
1/ créer un dossier de projet : sur GitHub create new repository notre projet s'appelle Exercice-Git-base-manip git clone https://github.com/Clarkd341/Exercise-Git-base-manip.git sur terminal visual code.

2/ créer 3 dossiers (html/css/js) : mkdir html, css, js 

3/ créer les fichiers index.html, index.js et styles.css dans leurs dossiers respectifs : New-Item -Path .\index.js -ItemType File 

pour vérifier si le fichier bien crée exemple : Get-Item -Path .\index.js a mettre dans le dossier js verifie si fichier a bien était créé. 


4/ mettre à jour l'ensemble dans le dossier remote  : tout d'abord faire un git status pour voir si sa était mis à jour si ça pas était

 Fait faire : un git add. Pour ajouter et ensuite un git commit -m "description de la modification" et un git push Origin main pour le mettre sur

 GitHub (Origin dépôt distant a défaut) et (main Branch local) ou si on crée une Branch on peut l'appeler dev et mettre sa a la place.


5/ créer une branche "dev" : git branch dev

6/ lister les branches git branch -a 

7/ se positionner sur la branche dev : git checkout dev

8/ modifier le fichier css  oui ensuite 

9/ mettre la modification a jour sur la branche dev  on fait enregistrement local et transfère avec git add. Suivi de git commit -m et git push origin dev.

10/ revenir sur la branche master et ouvrir le fichier css (voit-on la modif ?) git checkout main pour aller sur main.  non car la modifiaction a etait apporter a dev pas a main il faudrais refais le meme precessus sur main.

11/ fusionner la branche dev sur la branche master git merge dev transfer sur main le modification.

12/ verifier la modif css : oui

13/ retourner sur la branche dev et ajouter un fichier readme.md  sur GitHub. fait oui.

14/ faire un commit de ce fichier  git commit -m 

15/ visualiser les differences avec la commande adéquate : git diff

16/ créer deux nouvelles branches branch-a et branch-b

17/  dans chaque fichier READme de chaque branche, ajoutez une ligne spécifique (modification branch-a et branch-b par ex) tout se fait sur 

GitHub simple et rapide.

18/ comparez les deux branches avec la fonction adéquate :    git diff  

19/ mergez la branche a sur master :   git merge branch-a

20/ mergez la branche b sur master :      git merge branch-b
