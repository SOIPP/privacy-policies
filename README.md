# Politiques de confidentialité SOIPP

Ce dépôt public héberge une page web de confidentialité par extension ou plugin SOIPP, notamment pour fournir l’URL demandée dans le Chrome Web Store.

## Publication web

Activer GitHub Pages une seule fois : **Settings → Pages → Deploy from a branch → main → /(root)**.

Accueil prévu : <https://soipp.github.io/privacy-policies/>.

Une politique placée dans `cldictaphone/index.html` sera accessible à :

<https://soipp.github.io/privacy-policies/cldictaphone/>

Cette URL est un exemple de destination. La politique ClDictaphone sera ajoutée par son propriétaire ; le dépôt initial ne publie aucune politique produit.

## Ajouter un produit

1. Cloner `git@github.com:SOIPP/privacy-policies.git` avec son identité GitHub habituelle disposant de l’écriture sur ce dépôt.
2. Mettre `main` à jour avant de commencer.
3. Créer `<identifiant-produit>/index.html`, avec un identifiant stable en minuscules, sans espace.
4. Publier le texte propre au produit : nom exact, date de mise à jour et informations de contact, puis une description fidèle de ses pratiques relatives aux données. Le propriétaire du produit valide le texte et sa cohérence avec les déclarations du Chrome Web Store.
5. Ajouter un lien vers cette page dans l’accueil `index.html`.
6. Commiter puis pousser sur `main`. Après activation initiale de Pages, chaque push met le site à jour. Vérifier que la page HTTPS est effectivement accessible avant d’utiliser son URL dans le Chrome Web Store.

Les politiques restent autonomes : une modification sur un produit n’exige pas de republier son extension. Conserver les chemins déjà utilisés dans les fiches des stores.

## Identités et droits

Une clé SSH permet de pousser si le compte GitHub associé dispose du droit d’écriture sur **ce dépôt**. Une clé de déploiement limitée à un autre dépôt n’accorde pas cet accès. La clé n’a pas besoin d’être copiée dans ce dépôt, et l’activation de Pages n’est pas nécessaire à chaque publication.

Chaque propriétaire modifie la page de son produit. Le dépôt accueille uniquement des contenus destinés au public, sans sources privées ni données client. Aucun texte générique de ce dépôt ne constitue une politique déjà approuvée pour un produit.

## Structure

```text
.nojekyll
README.md
index.html
<identifiant-produit>/
    index.html
```

## Références

- [Exigences du Chrome Web Store sur les données et la confidentialité](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq)
- [Configurer une source de publication GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
