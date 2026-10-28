# Découvrir les réalités à partir des données

## Tableau complété

| Donnée observée | Valeur répétée | Réalité représentée | Identifiant proposé | Dépendance fonctionnelle |
|---|---|---|---|---|
| `nom_auteur` | Madani, Sara | Auteur | `email_auteur` | `email_auteur -> nom_auteur, prenom_auteur` |
| `nom_ville` | Tanger, Rabat | Ville | `id_ville` | `id_ville -> nom_ville` |
| `nom_categorie` | Développement, Actualité | Catégorie | `id_categorie` | `id_categorie -> nom_categorie` |

## Explication

### 1. Auteur
L'adresse `email_auteur` est unique pour chaque auteur. Elle permet de déterminer son nom et son prénom. Nous découvrons donc la réalité **Auteur**.

### 2. Ville
Les valeurs « Tanger » et « Rabat » apparaissent plusieurs fois. Elles représentent des villes. Nous proposons l'identifiant `id_ville` pour identifier chaque ville.

Dépendance fonctionnelle : `id_ville -> nom_ville`

### 3. Catégorie
Les valeurs « Développement » et « Actualité » apparaissent plusieurs fois. Elles représentent des catégories d'articles. Nous proposons l'identifiant `id_categorie` pour identifier chaque catégorie.

Dépendance fonctionnelle : `id_categorie -> nom_categorie`

## Conclusion

L'observation des identifiants et des répétitions permet de découvrir trois réalités : **Auteur, Ville et Catégorie**. Chaque réalité possède un identifiant permettant de déterminer ses données.

