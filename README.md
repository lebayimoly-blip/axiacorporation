# AXIA Corporation — Site Web

## Arborescence du projet

```
axia-website/
│
├── index.html                  ← Page d'accueil
│
├── css/
│   ├── main.css                ← Styles globaux (navbar, footer, boutons, layout)
│   ├── home.css                ← Styles spécifiques à la page d'accueil
│   ├── about.css               ← Styles de la page À Propos
│   ├── services.css            ← Styles de la page Services
│   ├── realisations.css        ← Styles de la page Réalisations
│   └── contact.css             ← Styles de la page Contact
│
├── js/
│   └── main.js                 ← JavaScript global (navbar, animations, formulaire)
│
├── images/                     ← Dossier pour vos images (logo, produits, etc.)
│   └── (ajouter vos images ici)
│
└── pages/
    ├── about.html              ← À Propos (équipe, mission, vision, valeurs)
    ├── services.html           ← Services (7 secteurs avec tarifs)
    ├── realisations.html       ← Réalisations (KPI, études de cas, projets)
    └── contact.html            ← Contact (formulaire + coordonnées)
```

## Instructions d'utilisation

### 1. Copier les fichiers
Copiez l'intégralité du dossier `axia-website/` dans votre hébergeur.

### 2. Ouvrir localement
Double-cliquez sur `index.html` pour ouvrir dans votre navigateur.
Aucun serveur nécessaire — c'est du HTML/CSS/JS pur.

### 3. Ajouter le logo
- Placez votre logo dans `images/logo.png`
- Il s'intègre facilement dans la navbar dans `main.css`

### 4. Ajouter vos photos
- Créez un dossier `images/`
- Ajoutez vos photos produits, équipe, bâtiments
- Remplacez les emojis dans les `.svc-visual` par vos images réelles :
  ```html
  <img src="../images/immobilier.jpg" alt="Immobilier Axia" />
  ```

### 5. Activer le formulaire de contact
Le formulaire simule l'envoi. Pour l'activer réellement :
- Option A : Utilisez **Formspree** (gratuit) — ajoutez `action="https://formspree.io/f/VOTRE_ID"` au formulaire
- Option B : Configurez un backend PHP ou Node.js

### 6. Déploiement
Hébergeurs recommandés :
- **Netlify** (gratuit, glisser-déposer le dossier)
- **Vercel** (gratuit)
- **cPanel** (hébergement classique)

## Technologies utilisées
- HTML5 sémantique
- CSS3 (variables, grid, flexbox, animations)
- JavaScript vanilla (ES6+)
- Google Fonts : Playfair Display + DM Sans
- Aucune dépendance externe

## Pages incluses
| Page | Fichier | Contenu |
|------|---------|---------|
| Accueil | index.html | Hero, secteurs, mission, impact, projets |
| À Propos | pages/about.html | Équipe dirigeante, responsables, valeurs |
| Services | pages/services.html | 7 secteurs avec tarifs détaillés |
| Réalisations | pages/realisations.html | KPI, études de cas, projets futurs |
| Contact | pages/contact.html | Formulaire + coordonnées complètes |
