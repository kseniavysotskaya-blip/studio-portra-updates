# Studio Portra — mises à jour

Espace public de publication du logiciel Studio Portra.

## Publication

GitHub Pages publie automatiquement la branche `main`.

- [Manifeste de mise à jour](https://kseniavysotskaya-blip.github.io/studio-portra-updates/latest.json)
- [Paquet 5.2.0](https://kseniavysotskaya-blip.github.io/studio-portra-updates/Studio-Portra-5.2.0.zip)

## Vérifications de la version 5.2.0

Le paquet contient uniquement quatre fichiers du logiciel et son manifeste `version.json`. Aucun dossier de photos, essai, réglage personnel ou donnée utilisateur n’est inclus.

Contrôles réalisés : empreintes SHA-256 des fichiers, installation dans une copie isolée, sauvegarde de la version précédente, conservation de données fictives et rejet des paquets altérés ou contenant un fichier photo supplémentaire.

SHA-256 du ZIP : `c5f7ae5c5f3e4a9f9b76b16d50fe057f2e11a83f8263663bf6ee344343767156`

Ces empreintes contrôlent l’intégrité ; elles ne constituent pas une signature indépendante de l’éditeur.

## État et limites

L’hébergement des fichiers ne signifie pas que l’installation automatique sur Mac est opérationnelle. La connexion de l’application au manifeste et le test complet dans l’application native restent à réaliser. La version 5.2.1 mentionnée dans une conversation antérieure n’est pas publiée ici.

Pour chaque future version : tester le logiciel, contrôler l’absence de données personnelles, valider le ZIP avec `release_manager.validate_bundle`, calculer son SHA-256 puis publier le paquet et `latest.json` ensemble. GitHub Pages assure ensuite le déploiement web. Aucun processus de génération automatique des nouvelles versions depuis les sources n’est encore configuré.
