# Pense-bête GIT 

Configuration initiale de GIT
- git config --global user.name "MON PSEUDO"
- git config --global user.email "MON_EMAIL"

Cloner un dépôt
- git clone https://github.com/Silocan/GameOfLife-JS.git

Ajouter un fichier
- git add NOM_DU_FICHIER

Valider la/les modification en cours
- git commit -m "COMMENTAIRE" NOM_DU_FICHIER
- git commit -am "COMMENTAIRE"

Déclarer un dépôt distant
- git remote add NOM_DEPOT URL_DEPOT

Envoyer les modifications sur un dépôt distant
- git push DEPOT_DISTANT branche_locale
