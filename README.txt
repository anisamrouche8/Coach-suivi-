COACH SUIVI — version 1

Contenu
- index.html : application
- manifest.webmanifest : configuration installable
- service-worker.js : cache hors ligne
- icon-192.png et icon-512.png : icônes

Fonctionnalités
- clients sans limite imposée par l'application
- forfaits avec séances restantes calculées automatiquement
- décompte manuel d'une séance avec confirmation
- ajout de séances au forfait
- historique et annulation d'un décompte (crédit restitué)
- recherche de clients
- export JSON de sauvegarde
- stockage local dans le navigateur

Installation sur iPhone
Pour installer comme une PWA, le site doit être servi en HTTPS. Déposez le contenu du dossier sur un hébergeur statique HTTPS (par exemple GitHub Pages). Ouvrez ensuite l'URL dans Safari > bouton Partager > Sur l'écran d'accueil.
Le simple fait d'ouvrir index.html comme un fichier ne permet pas l'installation PWA complète.

Limites
- aucune synchronisation entre appareils
- les données restent dans le stockage local de Safari et peuvent être perdues si les données du site sont effacées
- exportez régulièrement le fichier JSON via « Exporter les données »
- pas de comptes, e-mails automatiques, notifications push, paiements ni sauvegarde cloud
- application fournie comme prototype fonctionnel, à tester avec des données non sensibles avant utilisation professionnelle

Coût
- le code et l'application sont gratuits
- hébergement statique HTTPS possible gratuitement avec GitHub Pages
- un nom de domaine personnalisé est facultatif et généralement payant
