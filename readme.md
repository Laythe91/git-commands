# Commandes git
Liste des commandes git

## git init
- Permet d'initialiser un répertoire 

## git add
- Permet d'ajouter un fichier ou des modification dans le stagging

## git commit
- Permet d'enregistrer une modification en local
- Le message est important

## git push
- Permet de pousser les modifications en ligne

## git status
- Permet aussi de vérifier le statut du répertoire
- Permet de lister les modifications à traiter

## git log
- Permet de lister les modifications (git log --oneline)

## git branch 
- Permet de créer une branche

## git checkout
- Permet de passer d'une branche à une autre
- Permet de se déplacer d'une branche à une autre
- Avec l'option -b checkout créé la branche si elle n'existe pas

## git pull
- Permet de récupérer les modifications distantes

## git rebase
- Permet de récupérer les modifications de la branche mère
- Les modifications de la branche mère sont placées en-dessous des modifications de la branche courante
- Les modifications de la branche courante sont placées au-dessus des modifications de la branche mère

## git merge
- Permet de fusionner le contenu de deux branches
- l'ordre des commit n'est pas toujour sauvegarder
- Pour conserver l'ordre des commit il faut utiliser l'option --no-ff

## git reset
- Permet de supprimer un commit
- Permet de revenir à un commit défini par son identifiant
- Attention à utiliser avec précaution

## git diff 
- Permet de comparer deux commits

## git clone
- Permet de récupérer tout le projet