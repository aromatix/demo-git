Petit exercice git

à faire : 
1 - Créer un fichier nommé "README.txt" qui présente le projet
2 - Ajouter au moins 2 autres fichiers de votre choix
3 - Faire au moins 4 commits distincts montrant l’ajout puis la modification de certains fichiers

Actions faites :
1/ mkdir git-demo
2/ cd git-demo
3/ vi readme.txt  // ajout des taches à faire
4/ git init
5/ git add readme.txt
6/ git commit

 7/ cat > second-fichier.txt
 8/ git status
 9/ git add second-fichier.txt
10/ vi readme.txt  // ajout des actions faites jusqu'ici et enregistrement

11/ création du repository git-demo dans github
12/ ajout du repo : git remote add origin https://github.com/aromatix/demo-git.git
13/ MAJ readme.txt + git add "git_p2_activité.txt"  + git commit -am
git push origin master
