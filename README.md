# Galerie Fluide Bleu & Blanc

Une galerie photo immersive avec un thème bleu et blanc fluide, des animations organiques et des interactions dynamiques.

## 🎨 Caractéristiques

- **Design Biomorphique** : Formes organiques qui respirent et se transforment
- **Animations Fluides** : Morphing continu, flottement dynamique et transitions douces
- **Thème Bleu & Blanc** : Dégradés harmonieux et apaisants
- **Interactions Immersives** : Survol avec agrandissement fluide et respiration
- **Responsive** : Fonctionne sur tous les appareils
- **Simple & Léger** : HTML/CSS/JavaScript pur, sans dépendances complexes

## 🚀 Déploiement

### GitHub Pages

```bash
git push origin main
```

Activez GitHub Pages dans les paramètres du repository.

### Vercel

1. Connectez votre repository GitHub à Vercel
2. Vercel détectera automatiquement le fichier `index.html`
3. Cliquez sur "Deploy"

### Netlify

1. Connectez votre repository GitHub à Netlify
2. Définissez le répertoire de publication comme racine
3. Cliquez sur "Deploy"

## 📁 Structure

```
galerie-fluide-bleu-blanc/
├── index.html          # Fichier principal (HTML + CSS + JS)
├── README.md          # Documentation
├── .gitignore         # Configuration Git
└── public/            # Dossier pour les assets statiques
```

## 🎯 Utilisation

Ouvrez simplement `index.html` dans votre navigateur ou déployez sur n'importe quel serveur web statique.

## 💡 Personnalisation

Vous pouvez facilement modifier le fichier `index.html` :

**Images** : Remplacez les URLs dans le tableau `images` (ligne ~115)

```javascript
const images = [
    "votre-url-image-1.jpg",
    "votre-url-image-2.jpg",
    // ...
];
```

**Couleurs** : Modifiez les valeurs de gradient dans le CSS (ligne ~21)

```css
background: linear-gradient(-45deg, #0066CC, #003366, #E6F2FF, #ffffff, #004080);
```

**Titre** : Changez "L'Eau & L'Air" dans le HTML (ligne ~82)

**Animations** : Ajustez les durées et délais dans le CSS

## 📄 Licence

Libre d'utilisation
