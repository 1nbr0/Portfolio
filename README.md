# Portfolio

## Travail réaliser durant mon stage chez Motion4Ever

### Récap du 25/05/21 de 9h à 12h
- Mise en place de l’adresse mail motion4ever.com.
- Install OpenVPN + Chat Google pour la com avec référent de stage.
- Lecture et prise de connaissance du framework Laravel avec un tuto et la doc.
- Connexion OpenVPN + GitLab
- Git clone du projet tools
- Modif homestead + hosts -> pour le dev.tools.motion4ever.net
- Ajout fichier .env.
- Découverte d’un bug sur l’install vagrant up.
- En cours de résolution du problème avec mon référent de stage.

### Récap du 25/05/21 de 14h à 18h
- Chercher l’origine du problème pour vagrant up.
- Chercher solution au problème.
- Je me suis documenté sur plusieurs sites web différents pour trouver une solution (stackoverflow principalement) mais rien n’y fait.
- Découverte et observation du code sous Laravel.
- Explication des outils utilisé par Motion4Ever.
  
### Récap du 26/05/21 de 9h à 12h
- Compréhension du code :
    o DashWareController et BackupController (ce sont deux fichiers sur lesquels je travaillais).
- Install Laravel via Composer entre temps.
- Vu ensemble réponse aux questions + travaille à effectuer + install DB.

### Récap du 26/05/21 de 14h à 18h
- Récupération DB du serveur à ma machine local.
- Mise en place de la DB (import).
- Mise en place environnement de développement.
- Appropriation du code.
- Test pour la page login
- Page login fini reste le css à modifier.
- Manque plus que le commit et le push pour l’intégrer sur le serveur.

### Récap du 27/05/21 de 9h à 12h
- Présentation des locaux.
- Mise à dispo d’un post.
- J’ai regardé Valentin travailler sur un projet, il m’a expliqué ce qu’il était en train de résoudre comme problème. Explication du code dans le même temps.
- J’ai modifié le css, la page de login faite.
- Vagrant up fonctionnel ainsi que la VM, il y a des petits soucis qu’il va falloir que je règle.
- Git push effectué.

### Récap du 27/05/21 de 14h à 18h
- Correction bug vagrant lié aux versions de composer et php.
- Version php et composer modifié.
- Pull de la branch develop sur ma vagrant.
- Push de la page login sur le serveur.

### Récap du 28/05/21 de 9h à 12h
- Petit problème de mise en page repéré pour la page d’accueil Toolbox.
- Migration DB.
- Correction index.blade.php et style.css --> problème résolu.
- Push de la correction.
- http ERROR 500 apparu sur la page Backups.

<<<<<<< HEAD
Recap du du 28/05/21 de 14h à 18h
- Http Erreur 500 toujours pas résolu
- J’ai eu beaucoup de problème venant de mon pc, il est devenu extrêmement lent. Je l’ai redémarré, il semble aller mieux. J’espère ne plus rencontrer de problème comme ça sur mon pc. Je n’avance pas dans mon travail, c’est très frustrant.

### Récap du 31/05/21 de 9h à 12h
- Fichier hosts passé en exception sur Btdefender → prends pas en compte et continue de se commenter.
- Toujours en train de debug l’erreur 500. Cette erreur est présente que sur la page Backups.
- Réflexion et start d’une maquette pour la page Backups. Je m’inspire du Bootstrap que vous avez déjà utilisé pour le Toolbox.
  
### Récap du 31/05/21 de 14h à 18h
- Correction de l’erreur 500 → causé par des différences de versions.
- Re explication de la structure des pages Backups.
- RDV entretien pour alternance → Dois partir plus tôt.
- 
### Récap du 01/06/21 de 9h à 12h
- J’ai cherché l’origine du problème, au bout d’un certain temps j’ai trouvé.
- Je cherche maintenant à régler le souci en regardant plus attentivement à quel endroit ça bloque. (avec des var_dump() ; exit; ).

### Récap du 01/06/21 de 14h à 18h
- J’ai cherché toute l’après midi dans le code d’où pouvait venir le problème.
- J’ai cherché des solutions pour modifier l’encodage,
- Passage des fichiers txt qui étaient en CRLF en LF pour éviter les retours à la ligne.
- Je vais pouvoir travailler sur la mise en page des Backups.

### Récap du 02/06/21 de 9h à 12h
- Mise en page Backups sur une ligne.
- Récupération et Intégration du 6eme backups.
- Réflexion sur les future tableaux.

### Récap de la journée du 03/06/21
- J’ai repris le tableau mis à disposition dans d’autres pages pour l’inclure sur la page backups.
- J’ai modifié en fonction des données à recueillir des pages PROD BACKUP 1 à 6 dans le tableau.
- Toutes les données sont correctes. Il reste tout de même un petit souci au niveau des dates qui ne sont pas les plus récente mais les plus anciennes.
- Petit souci au niveau du push, j’ai été maladroit, rectification et push effectué correctement à la suite de la correction du souci.
- Mise en page de la popin. Toujours en cours.

### Récap de la journée du 04/06/21
- Mise en page de la popin.
- J’ai eu des soucis avec le VPN le matin, difficile d’avancer.
- Puis un souci avec les envois du fichier style.css sur le ftp due au souci avec le VPN.
- J’ai fait une boulette à ne pas enregistrer le style.css en local (ça m’apprendra).
- J’ai donc refait, en début d’après-midi, la mise en forme de la popin puis j’ai peaufiné la popin pour la rapprocher au plus près de l’exemple que mon tuteur m’a fourni.

### Récap de la journée du 07/06/21
- Travaille de réflexion sur la mise en place correct de BackupCommand.
- Recherche autour du code pour trouver les meilleures possibilités de tables en base de données.
- Deux tables sont ressorties de notre recherche, mise en place de Model. → A continuer.

### Récap de la journée du 08/06/21
- Création des fichiers migrations pour créer les tables et les colonnes.
- J’ai suivis la documentation Laravel + des tutos pour comprendre comment ça fonctionne.

### Récap de la journée du 09/06/21
- J’ai suivi la documentation Laravel + des tutos pour comprendre comment ça fonctionne. Je me suis embrouillé avec le tuto j’ai donc repris de zéro.
- J’ai dû faire face à une erreur (encore) qui a été corrigée, je n’avais plus de DB homestead.
- J’ai re écrit les colonnes à mettre dans les tables.
- J’ai repris et je me suis aidé quand nécessaire des autres migrations déjà faites.

### Récap de la journée du 10/06/21
- Je me suis attardé sur les inserts dans les deux tables que j’ai créés hier.
- J’ai beaucoup cherché en m’aidant de la doc et de tuto pour comprendre et ensuite re transcrire ce que j’ai lu et vu sur les Commands.
- Je ne suis pas sur du résultat pour l’instant.

### Récap de la journée du 11/06/21
- J’ai regardé ce les modifs que tu as fait pour les Commands et la mise en BDD des valeurs.
- Je travail sur le front et la récupération des données qui sont présentes dans la BDD.
- J’ai réussi à récupérer ces données.
- Reste à faire le front.

### Récap de la journée du 14/06/21
- Récupération des données en BDD.
- Json_decode des données +trie des données.
- Affichage en front des données en cours.

### Récap de la journée du 15/06/21
- Travaille sur le front.
- Récupération des données des deux tables pour affichage dans le tableau interactif.
- Commenter le code.

### Récap de la journée du 16/06/21
- Push du Front de la page Backup.
- Analyse du code pour envoyer une notification par mail, push en décommentant le code pour envoyer une notif.
- Regarder si DashWare et ses données sont en BDD.
- Création DashWareCommand.

### Récap de la journée du 17/06/21
- Création DashWareCommand.
- Création Model + Migration pour le DashWareCommand.
- Récupérer information de la variable $data à insert en BDD.
- Ecrire le code pour créer les colonnes et récupérer données puis les inserts dans la table en question.
- Création de la table dashwares avec les colonnes.

### Récap de la journée du 18/06/21
- Envoie des données en BDD.
- Rectification d’erreurs et de type de colonne et du code.
- Récupération des données de la table dashwares pour affichage.
- Modification du code dans le dashware.blade.php.
- Affichage en front des données.
- Problème avec le déclenchement des popin (JS) à corriger.

### Récap de la journée du 21/06/21
- Problème avec le déclenchement des popin (JS) pas résolue, j’ai cherché à comprendre comment elle se déclenchaient mais pas trouvé.
- Problème au niveau de l’affichage des fichiers erronés dans les popin.
- Travail de recherche également sur les erreurs liées aux notifications.
- Correction de ces erreurs.
- Essaie d’envoie de notification, changer des fichiers backup et dashware pour savoir si un mail s’envoie bien au moment d’une modification dans un fichier.

Le 22 Juin était mon dernier jour chez Motion4Ever.