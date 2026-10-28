# Entités finales du e-commerce

### 1. CLIENT
- `id_client`
- `nom_client`

### 2. COMMANDE
- `id_commande`
- `date_commande`
- `id_client`

### 3. PRODUIT
- `id_produit`
- `nom_produit`

### 4. LIGNE_COMMANDE
- `id_commande`
- `id_produit`
- `quantite_commandee`

**Identifiant composé de LIGNE_COMMANDE :** `id_commande, id_produit`