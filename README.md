# ⚡ Web3 Dashboard - Airdrop Hunter

> Ton centre de commande personnel pour le suivi d'airdrops, DeFi et activités Web3

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📋 Description

**Web3 Dashboard** est une application web single-page moderne et élégante pour gérer et suivre vos activités dans l'écosystème Web3. Organisez vos sites d'airdrop farming, plateformes DeFi, protocoles de staking et bien plus dans une interface intuitive inspirée du design cyberpunk.

### ✨ Fonctionnalités Principales

- 🎯 **Gestion de Sites** : Organisez vos plateformes Web3 par catégories personnalisables
- 📊 **Heatmap d'Activité** : Visualisez votre engagement quotidien style GitHub contributions
- 📈 **Statistiques en Temps Réel** : Suivez vos sites actifs, visites du jour et progression
- ✅ **Tracker de Visites** : Marquez automatiquement les sites visités chaque jour
- 💾 **Stockage Local** : Toutes vos données restent privées dans votre navigateur
- 🌐 **Multilingue** : Interface disponible en Français et Anglais
- 📥 **Import/Export** : Sauvegardez et partagez vos configurations en JSON
- 🎨 **Interface Moderne** : Design cyberpunk avec animations fluides et mode sombre

## 🚀 Démarrage Rapide

### Installation

Aucune installation requise ! C'est une application statique pure :

```bash
# Cloner le repository
git clone https://github.com/votre-username/web3-dashboard.git

# Ouvrir le fichier
cd web3-dashboard
open index.html  # ou double-clic sur le fichier
```

### Utilisation

1. **Ajouter une catégorie** : Cliquez sur "+ Nouvelle Catégorie" (ex: Airdrop Farming, Swap & DEX)
2. **Ajouter un site** : Cliquez sur "+ Ajouter un Site" et remplissez les informations
3. **Visiter un site** : Cliquez sur une carte de site pour l'ouvrir et marquer la visite
4. **Suivre votre progression** : Consultez la heatmap et les statistiques

## 🛠️ Technologies

- **HTML5** - Structure sémantique
- **CSS3** - Animations et design moderne (Grid, Flexbox, Custom Properties)
- **Vanilla JavaScript** - Logique applicative sans dépendances
- **LocalStorage API** - Persistance des données côté client

## 📸 Captures d'Écran

### Interface Principale
*Dashboard avec catégories, sites et statistiques en temps réel*

### Heatmap d'Activité
*Visualisation de votre engagement quotidien sur 365 jours*

## 🎯 Cas d'Usage

- **Airdrop Farmers** : Suivez vos interactions quotidiennes avec les protocoles testnet
- **DeFi Traders** : Organisez vos plateformes d'échange et de staking
- **Crypto Enthusiasts** : Centralisez tous vos bookmarks Web3
- **Portfolio Tracking** : Gardez trace de vos activités cross-chain

## 🔧 Fonctionnalités Avancées

### Système de Statuts
- 🟢 **Actif** : Sites que vous utilisez régulièrement
- 🔵 **Complété** : Airdrops ou tâches terminées
- 🟡 **En Pause** : Sites temporairement inactifs

### Import/Export
Exportez vos données en JSON pour :
- Sauvegarder votre configuration
- Partager vos listes avec d'autres
- Migrer entre appareils

### Réinitialisation Quotidienne
Le système réinitialise automatiquement les statuts de visite chaque jour à minuit.

## 🌍 Internationalisation

Le code inclut un **système i18n réutilisable** pour d'autres projets :
```javascript
// Pattern facilement transposable
const translations = { fr: {...}, en: {...} };
function setLanguage(lang) { /* ... */ }
```

## 📦 Structure du Projet

```
web3-dashboard/
├── index.html          # Application complète (HTML + CSS + JS)
└── README.md           # Documentation
```

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- 🐛 Signaler des bugs
- 💡 Proposer de nouvelles fonctionnalités
- 🔀 Soumettre des pull requests

## 📄 License

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 🙏 Remerciements

- Design inspiré par l'esthétique cyberpunk et les interfaces Web3
- Heatmap inspirée par GitHub Contributions
- Fonts : Space Mono & JetBrains Mono

## 📬 Contact

Des questions ou suggestions ? N'hésitez pas à ouvrir une issue !

---

⭐ **Si ce projet vous est utile, n'hésitez pas à lui donner une étoile !**
