# Studio Portra — mises à jour

Mises à jour de Studio Portra. Ce dépôt contient uniquement les fichiers du logiciel et les manifestes de publication, sans photos ni données utilisateur.

## Version 5.9.0

- Suppression des schémas avec confirmation intégrée, et actions Dupliquer / Supprimer sur le récapitulatif du test.

- Couleur et dimensions du fond visibles uniquement au clic. Nom du sujet visible uniquement à la sélection.

- Listes d’objectifs séparées Canon et Pentax, ajout personnalisé et conservation des objectifs déjà saisis. Canon RF 28–70 mm F 2,8 inclus.

- Appareils Canon et Pentax ajoutables au schéma, avec fenêtre de réglages individuels et conservation des réglages de base.
- Icône de rotation corrigée.

- Poignée ronde à deux flèches sous chaque éclairage sélectionné, y compris les draps. Maintenir le clic et déplacer la souris pour pivoter autour du centre, sans déplacement.

- Mes tests : dossiers nommés, page générale avec miniature de chaque schéma et sa photo numérique.
- Schémas nommés, création et déplacement entre dossiers. Les schémas existants sont conservés dans Tests existants.

- Le nom et les commandes apparaissent uniquement sur la source sélectionnée. Un clic dans le vide du schéma désélectionne les éléments.

- Suppression de la source ou du drap sélectionné avec Retour arrière ou Suppr, sans toucher aux champs de texte ni aux autres objets.

- Photos Canon : lecture du dossier EOS Utility et de ses sous-dossiers datés.
- Sélection de plusieurs photos pour chaque essai, sans remplacement automatique à chaque prise de vue.
- Copie locale des photos sélectionnées pour conserver les associations aux essais.
- Un seul schéma, avec le titre « Schéma d’éclairage » et ajout des sources dans le menu de droite.
- Lanterne chinoise de 85 cm directement accessible dans ce menu.

## Publication et vérification

GitHub Pages déploie automatiquement la branche `main`.

[Manifeste de mise à jour](https://kseniavysotskaya-blip.github.io/studio-portra-updates/latest.json)

[Paquet 5.9.0](https://kseniavysotskaya-blip.github.io/studio-portra-updates/Studio-Portra-5.9.0.zip)

Les paquets contiennent exclusivement les fichiers autorisés du logiciel et `version.json`. Le manifeste HTTPS fournit le SHA-256 du ZIP ; l’application contrôle également les empreintes de chaque fichier avant installation et conserve une sauvegarde de la version précédente. Ces empreintes vérifient l’intégrité, sans constituer une signature indépendante de l’éditeur.

Tests effectués : sélection multiple, migration des anciennes photos, absence de doublons, indépendance des essais, ajout de la lanterne, sous-dossiers Canon, copie et conservation locales des sélections, refus des chemins extérieurs au dossier, attente des fichiers en cours de transfert et validation du paquet.

## Futures versions

Chaque modification doit être développée et testée avant publication. Publier ensemble le nouveau ZIP vérifié et son `latest.json` déclenche le déploiement web. Le logiciel doit être configuré avec l’adresse du manifeste et l’option automatique activée pour récupérer les versions. La génération automatique des versions depuis les sources n’est pas configurée.

Les photos restent sur le Mac. Aucun dossier personnel, secret ou donnée d’essai ne doit être ajouté à ce dépôt.
