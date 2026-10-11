# Marée Messenger – application installable

Fichiers à déposer tels quels à la racine d'un site statique (GitHub Pages par exemple) :

- `index.html` : l'application ;
- `manifest.webmanifest` : nom, couleurs et icônes pour l'installation ;
- `sw.js` : fonctionnement hors connexion ;
- `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png` : icônes.

## Mise en ligne sur GitHub Pages

1. Créer un dépôt public, par exemple `maree-messenger`.
2. « Add file » → « Upload files » : glisser les fichiers ci-dessus, puis « Commit changes ».
3. « Settings » → « Pages » : source « Deploy from a branch », branche `main`, dossier `/ (root)`.
4. L'application est en ligne quelques minutes plus tard à l'adresse `https://<compte>.github.io/maree-messenger/`.

## Premier lancement (gestionnaire)

1. Ouvrir l'adresse dans Safari (iPhone) ou Chrome (Android), puis « Ajouter à l'écran d'accueil ».
2. Onglet Réglages : saisir la clé api-maree. Les 30 prochains jours de marées se chargent.
3. Onglet Bateau : renseigner le bateau, votre prénom et vos coordonnées de gestionnaire.
4. Onglet Calibrage : le message de mise à jour (MM1 PARAM) contient la clé ; l'envoyer aux équipiers, qui le collent dans Réglages.

La clé api-maree n'est pas écrite dans les fichiers publiés : elle circule seulement par le message de mise à jour.
