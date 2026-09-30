# Nessma — Au-delà de l'Odeur

Site vitrine (bêta) : catalogue des 11 parfums + réservation par WhatsApp.

## Modifier le site
Tout se règle en haut du `<script>` dans `index.html` :

- `CONFIG.whatsapp` : numéro au format international, sans `+` ni espaces (ex. `32470123456`)
- `CONFIG.instagram` / `CONFIG.snapchat` : liens des réseaux (laisser vide pour masquer l'icône)
- Liste `P` : pour remettre un parfum en stock, passer `dispo:false` à `dispo:true`
  (et ajouter ses notes `top`, `heart`, `base`, `int`)

Photos produits : dossier `img/` (nom du fichier = identifiant du parfum).
