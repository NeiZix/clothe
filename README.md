# Nebula Forge – Thème Tebex

Feuille de style complète pour moderniser un store Tebex avec une ambiance sombre néon, des cartes vitrées et des effets subtils.

## Contenu
- `styles/tebex-theme.css` : feuille de style principale du thème.

## Mise en place sur Tebex
1. Ouvrir le panneau Tebex → `Webstore` → `Theme`.
2. Basculer sur l’éditeur `Custom Theme` puis dans l’onglet `CSS`.
3. Coller le contenu de `styles/tebex-theme.css` (ou importer le fichier).
4. Sauvegarder et vider le cache Cloudflare si activé.

## Personnalisation rapide
Les variables définies dans `:root` contrôlent la palette et les rayons d’arrondi :

- `--color-primary`, `--color-secondary`, `--color-accent` pour les dégradés principaux.
- `--color-bg`, `--color-bg-alt`, `--color-surface` pour les fonds.
- `--radius-*`, `--shadow-*` pour le rendu des cartes.

Modifiez-les en haut du fichier pour ajuster le thème sans toucher au reste.

## Sections couvertes
- Navigation sticky translucide avec effet de soulignement animé.
- Hero/banner avec gradient animé, CTA multiples et type responsive.
- Grille de packages avec tags, prix mis en avant et hover lumineux.
- Modules latéraux (panier, dernières ventes, tops) avec verres dépoli.
- Boutons primaires/secondaires, formulaires, alertes et tableaux harmonisés.
- Animations discrètes (`floaty`) et breakpoints 1024/768/520 px.

## Conseils additionnels
- Ajouter votre logo en SVG transparent pour profiter des ombres portées.
- Utiliser l’option Tebex “Custom Background” pour uploader une image cohérente si besoin.
- Les classes de base (`.package`, `.module`, `.cart`, `.navbar`) correspondent au markup standard du thème Tebex ; adaptez les sélecteurs si vous avez un layout personnalisé.
