MYROUTINE — INSTALLATION

Contenu :
- index.html : application
- manifest.webmanifest : configuration installable
- sw.js : service worker de base

UTILISATION RAPIDE
1. Décompressez le ZIP.
2. Ouvrez index.html dans Chrome, Edge ou Firefox pour utiliser l'application.
3. Les modifications et tâches cochées sont sauvegardées dans le stockage local du navigateur.

INSTALLATION SUR ANDROID / PC
Pour l'installer comme une vraie application (PWA), les fichiers doivent être servis depuis une adresse HTTPS.
Par exemple, vous pouvez publier le dossier sur GitHub Pages, puis ouvrir son adresse dans Chrome/Edge et choisir
« Installer l'application » ou « Ajouter à l'écran d'accueil ».

RAPPELS
Les rappels utilisent les notifications du navigateur. Dans cette première version, l'application doit rester
ouverte et active pour vérifier les horaires. Les notifications fiables lorsque l'application est complètement
fermée nécessitent une version hébergée avec un service push et un serveur ; elles ne sont pas incluses ici.

DONNÉES
Les données sont stockées localement dans le navigateur de l'appareil. Elles ne se synchronisent pas
automatiquement entre Android et PC.
