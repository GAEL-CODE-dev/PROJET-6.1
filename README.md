# SCRAM SALON

Site vitrine pour un barbershop premium à Brazzaville. Projet portfolio démontrant la réalisation d'un site complet et responsive en HTML et CSS pur, sans aucune dépendance JavaScript.

**[Voir le site en ligne](https://GAEL-CODE-dev.github.io/PROJET-6.1/)**

---

## Aperçu

| Page | Description |
|------|-------------|
| **Accueil** | Hero section + section "Pourquoi Nous Choisir" (3 atouts) |
| **Services** | Page banner + grille de 4 prestations avec prix |
| **Contact** | Infos pratiques + formulaire de contact |

---

## Fonctionnalités

- **Zero JavaScript** — Toute l'interactivité est gérée en CSS uniquement
- **Menu hamburger** — Toggle via `<input type="checkbox">` + sélecteur CSS `:checked`
- **Responsive** — 4 breakpoints : desktop, tablette (≤1024px), mobile (≤768px), petit mobile (≤480px)
- **Navigation inter-pages** — 3 fichiers HTML avec liens croisés
- **Animations CSS** — Hover cards, transitions, smooth scroll
- **Validation formulaire** — Attributs HTML5 natifs (`required`, `type="email"`, `type="tel"`)
- **Design premium** — Dégradés, ombres portées, détails géométriques décoratifs

---

## Stack technique

| Technologie | Utilisation |
|-------------|-------------|
| HTML5 | Structure sémantique (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<nav>`) |
| CSS3 | Variables CSS, Flexbox, CSS Grid, Media Queries, Transitions |
| Google Fonts | Playfair Display (titres) + Inter (corps) |
| Font Awesome 6 | Icônes (CDN) |

**Pas de Bootstrap. Pas de JavaScript. Pas de frameworks.**

---

## Structure du projet

```
projet 6.1/
├── index.html        # Page d'accueil (hero + pourquoi nous choisir)
├── services.html     # Page services (4 prestations + atouts)
├── contact.html      # Page contact (infos + formulaire)
├── styles.css        # Feuille de style partagée
└── README.md
```

---

## Palette de couleurs

| Rôle | Couleur | Code |
|------|---------|------|
| Primaire | Or / Moutarde | `#D4AF37` |
| Secondaire | Noir charbon | `#1A1A1A` |
| Fond | Blanc cassé | `#F9F9F9` |
| Texte | Gris foncé | `#333333` |

---

## Démarrage local

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/GAEL-CODE-dev/PROJET-6.1.git
   ```
2. Ouvrir `index.html` dans un navigateur

Aucun serveur local nécessaire. Le site fonctionne directement en ouvrant le fichier HTML.

---


## Auteur

**Gael** — Développeur web
