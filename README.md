# QR·GEN — Générateur de QR Codes

> Transformez n'importe quel lien en QR code instantanément. Application web légère, sans backend, sans dépendances serveur.

## ✨ Fonctionnalités

- **Génération instantanée** — Entrez un lien et obtenez un QR code en un clic (ou avec `Entrée`)
- **Auto-complétion d'URL** — Le préfixe `https://` est ajouté automatiquement si absent
- **Personnalisation complète** — Couleur du QR, couleur du fond, taille (128px à 400px)
- **Téléchargement PNG** — Exportez votre QR code en haute résolution
- **Partage natif** — Partagez directement depuis mobile via l'API Web Share
- **Historique persistant** — Les 8 derniers liens générés sont sauvegardés localement
- **Compteur de générations** — Suivi du nombre total de QR codes créés
- **100% client-side** — Aucune donnée envoyée à un serveur

---

## 🚀 Démo

Ouvrez simplement le fichier `qr-generator.html` dans votre navigateur — aucune installation requise.

---

## 📦 Installation

```bash
# Cloner le dépôt
git clone https://github.com/votre-pseudo/qr-gen.git

# Accéder au dossier
cd qr-gen

# Ouvrir dans le navigateur
open qr-generator.html
```

Ou déployez en ligne (voir section [Déploiement](#-déploiement)).

---

## 🛠️ Technologies utilisées

| Technologie | Usage |
|-------------|-------|
| HTML5 | Structure de l'application |
| CSS3 | Styles, animations, layout |
| JavaScript ES6 | Logique, interactions, localStorage |
| [QRCode.js](https://github.com/davidshimjs/qrcodejs) | Génération des QR codes (CDN) |
| Google Fonts (Bebas Neue, DM Mono) | Typographie |

Aucun framework, aucun bundler, aucune dépendance npm — un seul fichier HTML suffit.

---

## 🎨 Design

L'interface adopte une esthétique **industrielle sombre** avec :
- Palette noir profond / jaune acide (`#e8ff47`)
- Typographie contrastée : *Bebas Neue* (titres) + *DM Mono* (corps)
- Grille de fond subtile et coins décoratifs
- Animations CSS soignées (fade-in, toast, blink)

---
