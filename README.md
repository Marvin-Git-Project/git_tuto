# Documentation du tuto GitHub

## Initialisation du dépot

/*
    bash 
    git-init
    git remote add origin SSH_du_REPO_GITHUB
        git remote remove origin  --> Si besoin de supprimer pour la l.8
    git status
    git add me "NOM_FICHIER"
    git commit
        git config --global user.name "Marvin"
        git config --global user.email "monMailGITHUB.com"
        git config --list
        git commit --> Penser un donner un nom à la sauvegarde
    git push origin main
*/

##  Vérification commit
/*  
    git log  (voir les commit effecués, appuyer sur q pour quitter)
    git show (info supplémentaires)
*/

## Retour en arrière avant sauvegarde
/*
    git add NOM_FICHIER
    git restore --staged NOM_FICHIER  (revenir en arrière | fonctionne uniquement avant un commit)
*/

## Rédiger un bon commit (entreprise)

/*
    Titre du commmit

    Description de notre commit avec des infos sur l'évolution du projet
*/

##  Créer une branche

/*
    git checkout -b develop
    git status (voir l'état du projet)
    git branch (voir les branches)
    git add FICHIER (si modif)
    git commit -m "Titre de la sauvegarde"
*/