# Horizon Ligne – Thème Tebex

Feuille de style pensée pour 2025 : palette neutre, typographie nette et composants modulaires inspirés du e-commerce haut de gamme (aucun effet néon / cyberpunk).

## Contenu
- `styles/tebex-theme.css` : feuille de style principale du thème.

## Mise en place sur Tebex
1. Ouvrir le panneau Tebex → `Webstore` → `Theme`.
2. Basculer sur l’éditeur `Custom Theme` puis dans l’onglet `CSS`.
3. Coller le contenu de `styles/tebex-theme.css` (ou importer le fichier).
4. Sauvegarder et vider le cache Cloudflare si activé.

## Personnalisation rapide
Les variables définies dans `:root` contrôlent tout le langage visuel :

- `--color-primary`, `--color-primary-hover`, `--color-accent` pour les actions.
- `--color-bg`, `--color-bg-alt`, `--color-surface`, `--color-surface-muted` pour les fonds.
- `--radius-*`, `--shadow-*`, `--gap-section` pour le rythme et la rondeur.

Ajoutez ou remplacez ces variables pour ajuster le thème sans modifier les composants.

## Sections couvertes
- Navigation sticky translucide avec badges arrondis.
- Hero/banner minimaliste, CTA empilables et meta info.
- Grille de packages, stat-cards, tags, badges et statuts homogènes.
- Modules latéraux (panier, dernières ventes, tops) + checkout épuré.
- Boutons primaires/secondaires, formulaires, alertes, tableaux et badges.
- Breakpoints 1024/768/540 px + respect du `prefers-reduced-motion`.

## Conseils additionnels
- Chargez un logo clair (SVG ou PNG 2x) pour rester net sur fond blanc.
- Conserviez des visuels produits avec fond neutre afin de garder l’ambiance premium.
- Les sélecteurs ciblent le markup par défaut de Tebex (`.package`, `.module`, `.cart`, `.navbar`). Adaptez-les si votre thème custom renomme les blocs.
- Combinez ce CSS avec les blocs HTML personnalisés Tebex pour injecter des timelines, FAQ ou galeries sans casser la grille.
