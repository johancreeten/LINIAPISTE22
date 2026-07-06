# Prototype LINIA — Piste 2 : Le Parcours créatif

Prototype statique HTML/CSS/JS pour présenter LINIA comme un guide créatif : envie, atelier, matériel, conseil, action.

## Fichiers créés
- `index.html` : page complète sémantique et SEO local.
- `css/styles.css` : design system natif responsive.
- `js/main.js` : menu mobile, reveal, sticky CTA.
- `assets/svg/` : ligne de parcours, pictogrammes et carte décorative.
- `assets/placeholders/` : visuels locaux de démonstration.
- `docs/` : synthèse, crédits, contrôle qualité.

## Lancer en local
```bash
python3 -m http.server 8000
```
Ouvrir `http://localhost:8000`.

## Tester sur smartphone
Connecter ordinateur et smartphone au même Wi‑Fi, puis ouvrir `http://IP-DE-L-ORDINATEUR:8000`.

## Publier sur GitHub Pages
Pousser le dépôt sur GitHub, activer Pages sur la branche courante et choisir la racine du dépôt.

## Transposition WordPress / Gutenberg
Les sections utilisent des classes `wp-section`, `wp-container`, `wp-card-grid`, `wp-split` pour faciliter la conversion en blocs Gutenberg/groupes/colonnes.

## Transposition WooCommerce
Les cartes `wc-product-card` et `wc-workshop-card` préfigurent des produits WooCommerce.

## Logique atelier
Un atelier peut devenir un produit WooCommerce virtuel avec stock limité correspondant au nombre de places disponibles.

## Points à adapter plus tard
Vraies photos définitives, adresse, horaires, produits réels, ateliers réels, fiches parcours, intégration WooCommerce, paiements Stripe/Mollie, Google Maps, formulaires, avis clients, textes légaux.
