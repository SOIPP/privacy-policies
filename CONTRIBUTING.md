# Contribuer aux politiques de confidentialité

L’accueil et le README s’adressent aux personnes qui consultent les politiques. Les indications de publication sont regroupées dans ce document.

## Publier une politique

1. Mettre à jour la branche `main` du dépôt `SOIPP/privacy-policies`.
2. Créer `<identifiant-produit>/index.html`, avec un identifiant stable en minuscules, sans espace.
3. Rédiger une politique propre au produit, datée, avec des coordonnées de contact et une description fidèle de ses pratiques relatives aux données.
4. Faire valider le contenu par le responsable du produit et vérifier sa cohérence avec les déclarations de l’extension sur les stores.
5. Ajouter le lien dans la section « Consulter une politique » de l’accueil. À la première publication, remplacer le message d’attente par la liste des politiques.
6. Commiter et pousser les changements. GitHub Pages publie automatiquement la branche `main`, depuis la racine du dépôt.
7. Vérifier l’accessibilité de la page HTTPS après le déploiement avant d’utiliser son URL dans une fiche produit.

Exemple de chemin : `cldictaphone/index.html`.

URL correspondante après publication : `https://soipp.github.io/privacy-policies/cldictaphone/`.

## Mettre à jour une politique

Conserver l’URL déjà publiée et actualiser la date du document lorsque son contenu change. Mettre à jour uniquement les informations du produit concerné et son entrée dans l’accueil.

Publier uniquement du contenu destiné au public. Les sources privées, secrets et données client n’ont pas leur place dans ce dépôt.

## Références

- [Exigences du Chrome Web Store sur les données et la confidentialité](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq)
- [GitHub Pages](https://docs.github.com/en/pages)
