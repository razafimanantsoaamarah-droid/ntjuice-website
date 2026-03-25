# NTJuice – Jus naturels de Madagascar

<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/eb78a661-0f2a-4e26-a464-682f884ca0e4" />

**NTJuice** est un site vitrine fictif pour une marque de jus de fruits naturels pressés à froid, originaire de Madagascar.  
Le site met en avant l'authenticité des produits, la fraîcheur des ingrédients et l’engagement pour une agriculture durable.

---

## Aperçu du projet

| Section | Description |
|--------|-------------|
| **Hero** | Présentation immersive avec fond animé, feuilles SVG, cercles fruités et carrousel de bouteilles (CSS pur) |
| **Valeurs** | Bandeau défilant (marquee) listant les engagements de la marque |
| **À propos** | Histoire de NTJuice, chiffres clés, photo d’atelier |
| **Produits** | Grille responsive présentant 4 jus signature (prix, description, bouton ajouter) |
| **Newsletter** | Inscription avec image de fond et formulaire |
| **Footer** | Liens, informations légales, logo |

---

## Fonctionnalités

- **100% CSS** – aucun JavaScript pour les animations de scroll, le carrousel, le menu burger (checkbox hack)  
- **Responsive** – s’adapte à tous les écrans (mobile, tablette, desktop) grâce aux unités `clamp()`, `vw`, `%` et media queries  
- **Animations scroll** – effet d’apparition (`slideUpReveal`) sans JS, utilisant `animation-timeline: view()`  
- **Carrousel de bouteilles** – rotation automatique infinie avec `@keyframes`  
- **Menu hamburger** – fonctionnel sans JavaScript, basé sur une checkbox CSS  
- **Icônes vectorielles** – SVG intégrés pour la marque, les valeurs et les décorations  
- **Palette de couleurs** – orange/vert inspirée des fruits tropicaux  

---

## Technologies utilisées

- **HTML5**  
- **CSS3** (Flexbox, Grid, `@keyframes`, `clamp()`, `@media`, `animation-timeline`, `backdrop-filter`)  
- **Aucune librairie externe** – tout est fait en pur CSS  

---

## Structure du projet

```
ntjuice-website/
├── index.html                # Page principale
├── assets/
│   ├── images/
│   │   ├── orange.png        # bouteille orange
│   │   ├── ananas.png        # bouteille ananas
│   │   ├── raisin.png        # bouteille raisin
│   │   ├── fraise.png        # bouteille fruits rouges
│   │   └── hero-preview.png  # aperçu du site (à ajouter pour le README)
│   └── (autres images)
└── README.md
```

> **Note** : Les images des bouteilles utilisées dans la démo sont des placeholders ; vous pouvez les remplacer par vos propres assets.

---

## Installation

1. **Cloner le dépôt**  
   ```bash
    https://github.com/razafimanantsoaamarah-droid/ntjuice-website.git
   ```
2. **Ouvrir le fichier** `index.html` dans votre navigateur  
   Pas de serveur nécessaire, le site fonctionne en local.

---

## Utilisation

Le site est prêt à être déployé sur n’importe quel hébergement statique (GitHub Pages, Netlify, Vercel).  
Il suffit de copier l’intégralité des fichiers et de servir le dossier racine.

---

## Captures d’écran

### Hero et carrousel
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/5f3df0cd-432c-4bf8-92f0-c59e8ce8f4ee" />

### Grille produits
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/dfa951ee-bccf-4591-a85e-d04d23dc8489" />

### Section À propos
<img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/2f36e72f-cf1e-4897-bc98-e643ec4a3d5c" />

---

## Personnalisation

- **Couleurs** : modifiez les variables CSS dans `:root` (--orange, --green, etc.)  
- **Contenu textuel** : adaptez les paragraphes dans les sections `#about`, `#products` et la newsletter  
- **Images** : remplacez les placeholders par vos propres fichiers dans `assets/images/` et mettez à jour les chemins dans le HTML  
- **Carrousel** : vous pouvez ajouter ou retirer des slides en modifiant les éléments `.juice-slide` et les animations correspondantes

---

## Contributions

Les contributions sont les bienvenues !  
Merci de soumettre une pull request ou d’ouvrir une issue pour toute suggestion d’amélioration.

---

## Licence

Ce projet est sous licence **MIT**. Vous êtes libre de l’utiliser, de le modifier et de le redistribuer.

---

## Remerciements

- Inspiration des effets CSS : [Prismic CSS Scroll Effects](https://prismic.io/blog/css-scroll-effects)  
- Technique du menu burger sans JS : communauté CSS  
- Images placeholder : [Placehold.co](https://placehold.co)

---

**NTJuice** – la fraîcheur de Madagascar dans chaque gorgée.  
```
