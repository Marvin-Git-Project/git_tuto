# Documentation du tuto GitHub

## Initialisation du dépot

/*

    git init (initialise un dépôt Git en local → crée le dossier caché .git)

                                OU FAIRE

    git remote add origin SSH_du_REPO_GITHUB  
    (connecte le dépôt local en SSH à un dépôt distant sur GitHub appelé "origin")

        git remote remove origin (supprime le lien avec le dépôt distant si on s’est trompé d’URL)

    git status (affiche l’état des fichiers : modifiés, ajoutés, en attente de commit)

    git add NOM_FICHIER (ajoute un fichier à la zone de préparation avant le commit)

    git commit (crée une sauvegarde locale avec un message descriptif)
        SI PB : 
        git config --global user.name "Marvin"
        git config --global user.email "monMailGITHUB.com"
        git config --list

    git push origin main (envoie les commits locaux vers la branche main du dépôt distant)

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
    git checkout -b develop (création de la branche "develop")
    git status (voir l'état du projet)
    git branch (voir les branches)
    git add FICHIER (si modif)
    git commit -m "Titre de la sauvegarde"
    git push origin develop
*/

## Pousser une branche externe dans la principale

/*
    git branch (voir où je suis)
    git checkout main (on bascule sur la branche main)
    git merge develop (on envoi les données de develop dans main)
    git push origin main
*/
