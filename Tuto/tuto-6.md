# Entités finales du Blog

## 1. ARTICLE
---------------
- `id_article`
- `titre_article`
- `contenu_article`
- `date_publication`
- `statut_article`
- `image_article`
- `id_auteur`
- `id_categorie`

## 2. AUTEUR
---------------
- `id_auteur`
- `nom_auteur`
- `prenom_auteur`
- `email_auteur`
- `id_ville`

## 3. VILLE
---------------
- `id_ville`
- `nom_ville`

## 4. CATEGORIE
---------------
- `id_categorie`
- `nom_categorie`
- `description_categorie`

## Conclusion

Les données du Blog sont regroupées en quatre entités : Article, Auteur, Ville et Catégorie.

Les données répétitives ont été isolées dans des entités séparées. Les identifiants `id_auteur`, `id_categorie` et `id_ville` permettent de remplacer les données répétées dans les entités concernées.