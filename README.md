# Hexacup

### Dans ce repos, deux scripts : mdp et clear

Le script **mdp** génère des mots de passe aléatoires et les enregistre dans un fichier. Il crée un dossier "data" s'il n'existe pas déjà, puis récupère le numéro de génération en vérifiant les fichiers existants dans ce dossier. Il génère ensuite 5 mots de passe différents en les préfixant avec "Hexacup" et en ajoutant des caractères aléatoires. Chaque mot de passe est affiché à l'écran et enregistré dans un fichier correspondant.

Un autre script **clear** de nettoyage des dossiers permettant de vérifier si le dossier "data" existe. S'il existe, il demande une confirmation avant de le supprimer. Si l'utilisateur confirme, le script supprime le dossier "data" et son contenu. Sinon, il affiche un message indiquant que la suppression a été annulée. Si le dossier "data" n'existe pas, le script affiche simplement un message indiquant que le dossier n'existe pas.
