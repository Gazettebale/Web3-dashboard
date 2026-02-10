# ⚡ Web3 Dashboard

> Your personal command center for tracking and organizing multi-chain onchain activities

An elegant and minimalist dashboard to track your Web3 activities, manage your favorite protocols, and visualize your daily onchain interactions. 100% client-side, no database required.

## ✨ Features

### 🎯 Site Management
- **Organize by categories**: Create custom categories (DEX, Staking, Bridges, etc.)
- **Multiple statuses**: Active, Completed, Paused
- **Daily tracking**: Automatically mark visited sites (✅)
- **Custom descriptions**: Add notes for each protocol

### 📊 Activity Visualization
- **GitHub-style heatmap**: Visualize your activity over 365 days
- **Real-time statistics**: 
  - Total sites count
  - Active sites
  - Sites visited today
  - Number of categories

### 🌍 Multilingual Support
- **French / English**: Instant language switching
- **Reusable pattern**: i18n code easily adaptable to other projects

### 💾 Local Storage
- **100% offline**: Everything works in your browser
- **JSON Export/Import**: Backup and share your data
- **Automatic daily reset**: Visits reset every day

## 🎨 Interface

- **Cyberpunk design**: Dark theme with neon accents (green/blue)
- **Smooth animations**: Modern transitions and hover effects
- **Responsive**: Optimized for mobile and desktop
- **Custom fonts**: Space Mono + JetBrains Mono

## 🚀 Installation

### Option 1: Direct use
1. Clone the repo:
```bash
git clone https://github.com/your-username/web3-dashboard.git
cd web3-dashboard
```

2. Open `index.html` in your browser

That's it! No server needed.

### Option 2: Deployment
- **GitHub Pages**: Push and enable Pages in settings
- **Vercel/Netlify**: Drag & drop the HTML file
- **Render**: Static site with auto-deploy from GitHub

## 📖 Usage

### Add a site
1. Click **"+ Add Site"**
2. Fill in the information:
   - Protocol name
   - URL
   - Description (optional)
   - Status
   - Category
3. Save

### Create a category
1. Click **"+ New Category"**
2. Name your category (e.g., "🌉 Cross-chain Bridges")
3. Add sites to this category

### Track your activity
- Click on any site card to open it
- The site will open in a new tab
- It will be automatically marked as "visited today" ✅
- Your heatmap will update

### Export your data
1. Click **"📥 Export"**
2. A JSON file will be downloaded
3. Keep it as backup or share it

## 🛠️ Customization

### Change colors
In the `:root` CSS section:
```css
--accent-primary: #00ff88;  /* Neon green */
--accent-secondary: #0088ff; /* Neon blue */
--accent-warning: #ffaa00;   /* Orange */
```

### Add a language
1. Add your language to the `translations` object:
```javascript
const translations = {
    fr: { /* ... */ },
    en: { /* ... */ },
    es: { // New language
        subtitle: "Tu centro de comando...",
        // ...
    }
};
```

2. Add the button in HTML:
```html
<button class="lang-btn" onclick="setLanguage('es')">ES</button>
```

## 🔧 Tech Stack

- **HTML5**: Semantic structure
- **CSS3**: CSS Variables, Grid, Flexbox, Animations
- **Vanilla JavaScript**: No dependencies
- **LocalStorage API**: Data persistence
- **Google Fonts**: Space Mono & JetBrains Mono

## 📁 Structure

```
web3-dashboard/
│
├── index.html          # Complete application (single-file)
└── README.md          # This file
```

## 🎓 Reusable i18n Pattern

The translation system is **copy-paste ready** for your other projects:

```javascript
// 1. Copy the translations object
const translations = { fr: {...}, en: {...} };

// 2. Copy the functions
function setLanguage(lang) { /* ... */ }
function applyTranslations() { /* ... */ }

// 3. Add data-i18n on your HTML elements
<h1 data-i18n="title">My Title</h1>

// 4. Add the switcher
<div class="lang-switcher">
    <button onclick="setLanguage('fr')">FR</button>
    <button onclick="setLanguage('en')">EN</button>
</div>
```

## 💡 Use Cases

- **Multi-chain users**: Daily tracking of protocols across different blockchains
- **DeFi enthusiasts**: Monitor staking, liquidity, and yield platforms
- **NFT collectors**: Organize marketplaces and mint sites
- **Web3 builders**: Keep tabs on projects and protocols you're testing

## 🤝 Contribution

PRs are welcome! For major changes:
1. Fork the project
2. Create a branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Roadmap

- [ ] CSV export for advanced tracking
- [ ] Wallet integration (verify real claims)
- [ ] Daily notifications
- [ ] "Focus" mode with timer
- [ ] Custom tags per site
- [ ] Advanced filters

## 📄 License

MIT License - Use, modify, share freely!

## 🌟 Show Your Support

If this project helps you organize your Web3 activities, feel free to:
- ⭐ Star the repo
- 🐦 Share on Twitter/X
- 🔄 Fork for your own needs

---

**Made with ⚡ for the Web3 community**

*Disclaimer: This project is a personal tool. DYOR (Do Your Own Research) before interacting with any Web3 protocols.*
