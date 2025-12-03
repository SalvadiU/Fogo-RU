# Fogo Documentation - Russian Translation 🇷🇺

![Fogo](https://img.shields.io/badge/Fogo-Documentation-orange)
![Language](https://img.shields.io/badge/Language-Russian-blue)
![GitBook](https://img.shields.io/badge/GitBook-Ready-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

Complete Russian translation of [Fogo Community Documentation](https://community-docs.fogo.io).

**[📖 View Documentation](#)** | **[🚀 Quick Start](QUICKSTART.md)** | **[⚙️ Setup Guide](SETUP.md)** | **[🤝 Contribute](CONTRIBUTING.md)**

---

## 🔥 About Fogo

Fogo is the **fastest SVM-compatible blockchain**, built for speed, fairness, and performance.

- ⚡ **40ms block times**
- 🎯 **1.3s finality**
- 🌐 **Solana VM compatible**
- 🚀 **Real-time DeFi experience**

---

## 📚 Documentation Contents

### ✅ Fully Translated Pages

| Page | Description | Status |
|------|-------------|--------|
| **Overview** | What is Fogo, key features | ✅ Complete |
| **Getting Started** | Quick start guide, wallet setup | ✅ Complete |
| **Transferring to Fogo** | Portal Bridge, cross-chain transfers | ✅ Complete |
| **Ecosystem** | All projects (Ambient, Valiant, etc.) | ✅ Complete |

### 📂 Repository Structure

```
fogo/
├── README.md                           # 🏠 Overview (Main page)
├── SUMMARY.md                          # 📑 Navigation structure
├── getting-started/
│   ├── README.md                      # 🚀 Getting Started
│   ├── transferring-to-fogo.md        # 🌉 Transferring guide
│   └── ecosystem.md                   # 🌟 Ecosystem overview
├── SETUP.md                           # ⚙️ GitBook setup instructions
├── QUICKSTART.md                      # ⚡ 5-minute deploy guide
├── CONTRIBUTING.md                    # 🤝 Contribution guidelines
├── PROJECT_INFO.md                    # 📋 Project information
├── book.json                          # 📖 GitBook configuration
├── .gitbook.yaml                      # 🔧 GitBook sync config
└── package.json                       # 📦 NPM dependencies
```

---

## 🚀 Quick Deploy to GitBook

### Option 1: GitHub Integration (Recommended)

```bash
# 1. Push to GitHub
git init
git add .
git commit -m "Russian Fogo documentation"
git remote add origin https://github.com/YOUR-USERNAME/fogo-docs-ru.git
git push -u origin main

# 2. Import to GitBook
# - Go to gitbook.com
# - New Space → Import from GitHub
# - Select your repository
# - Done! 🎉
```

### Option 2: Local Preview

```bash
# Install GitBook CLI
npm install -g gitbook-cli

# Navigate to project
cd fogo

# Install plugins
gitbook install

# Preview at http://localhost:4000
gitbook serve
```

### Option 3: Direct Upload

1. Download repository as ZIP
2. Go to GitBook → New Space → Import
3. Upload ZIP
4. Configure and publish

**Full instructions**: [SETUP.md](SETUP.md)  
**Quick guide**: [QUICKSTART.md](QUICKSTART.md)

---

## ✨ Features

- ✅ **100% Translated**: All pages from original documentation
- ✅ **GitBook Ready**: One-click deployment
- ✅ **Auto-Sync**: GitHub integration for easy updates
- ✅ **SEO Optimized**: Proper meta tags and structure
- ✅ **Search Enabled**: Russian language search support
- ✅ **Mobile Friendly**: Responsive design
- ✅ **Code Blocks**: Syntax highlighting
- ✅ **Navigation**: Smart sidebar with expandable sections

---

## 🌐 Translations & Terminology

### Translation Principles

- ✅ Consistent terminology across all pages
- ✅ Technical terms properly transliterated
- ✅ Project names kept in English
- ✅ Explanations added where needed
- ✅ Formal tone (вы instead of ты)

### Key Terms

| English | Russian | Notes |
|---------|---------|-------|
| Blockchain | Блокчейн | No translation |
| Staking | Стейкинг | Transliteration |
| DeFi | DeFi | Keep as-is |
| Smart Contract | Смарт-контракт | With hyphen |
| Liquidity Pool | Пул ликвидности | |
| Perpetuals | Перпетуальные контракты | Full translation |
| Colocation | Совместное размещение | + explanation |
| Sessions | Сессии | But "Fogo Sessions" stays |

**Never translate**: Ambient, Valiant, Pyron, FogoLend, Brasa, FluxBeam, Invariant, Portal Bridge

---

## 🤝 Contributing

We welcome contributions from the community!

### How to Help

- 🐛 **Fix typos/errors**: Create a PR
- 💡 **Improve translations**: Open an issue first
- 📝 **Add new content**: Check original site for updates
- 🔄 **Sync updates**: Help keep docs current

**See**: [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines

### Contributors

<a href="https://github.com/YOUR-USERNAME/fogo-docs-ru/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=YOUR-USERNAME/fogo-docs-ru" />
</a>

---

## 📈 Project Status

- [x] Initial setup
- [x] Overview page translated
- [x] Getting Started translated
- [x] Transferring guide translated
- [x] Ecosystem page translated
- [x] GitBook configuration
- [x] Documentation for contributors
- [ ] Deploy to production
- [ ] Announce to community
- [ ] Set up auto-sync
- [ ] Monitor for updates

---

## 🔗 Links

- 📖 **Original Docs**: https://community-docs.fogo.io
- 🌐 **Fogo Website**: https://fogo.io
- 📚 **GitBook**: https://docs.gitbook.com
- 💬 **Community**: Discord / Telegram

---

## 📋 Requirements

### For Local Development

- Node.js 12+ 
- npm or yarn
- gitbook-cli

### For GitBook Deployment

- GitBook account (free)
- GitHub account (for auto-sync)
- Or direct upload (no requirements)

---

## 🛠️ Technical Details

### GitBook Plugins

- `search-pro`: Enhanced search with Russian support
- `page-toc`: Auto table of contents
- `back-to-top-button`: Easy navigation
- `expandable-chapters`: Collapsible sidebar
- `sharing`: Social media buttons

### Configuration

- **Language**: Russian (ru)
- **Root**: `./`
- **Summary**: `SUMMARY.md`
- **README**: `README.md`

---

## 📜 License

MIT License - see [LICENSE](LICENSE) file

This is a community translation project. Original content © Fogo Team.

---

## 🙏 Acknowledgments

- **Fogo Team**: For creating amazing blockchain technology
- **Original Documentation**: Community-docs.fogo.io
- **Contributors**: Everyone who helps improve this translation
- **GitBook**: For excellent documentation platform

---

## 📞 Support

### Questions about Translation?

- 💬 Open a [GitHub Issue](https://github.com/YOUR-USERNAME/fogo-docs-ru/issues)
- 📧 Contact maintainers
- 💭 Join community discussions

### Questions about Fogo?

- 🌐 Visit [fogo.io](https://fogo.io)
- 💬 Join Discord/Telegram
- 📖 Read [original docs](https://community-docs.fogo.io)

---

## 🎯 Roadmap

### Phase 1: Core Documentation ✅

- [x] Overview
- [x] Getting Started
- [x] Transferring to Fogo
- [x] Ecosystem

### Phase 2: Deployment 🚀

- [ ] Deploy to GitBook
- [ ] Configure custom domain
- [ ] Set up auto-sync
- [ ] Announce to community

### Phase 3: Expansion 📈

- [ ] Add new pages as they appear
- [ ] Community tutorials
- [ ] Developer guides
- [ ] API documentation
- [ ] Video content

### Phase 4: Maintenance 🔄

- [ ] Regular sync with original
- [ ] Community contributions
- [ ] Quality improvements
- [ ] SEO optimization

---

## 📊 Statistics

- **Pages**: 4 main pages
- **Words**: ~8,000+ translated
- **Language**: Russian
- **Format**: Markdown
- **Platform**: GitBook
- **Status**: Ready for deployment

---

## 🌟 Star History

If you find this useful, please star the repository! ⭐

```bash
# Clone and start contributing
git clone https://github.com/YOUR-USERNAME/fogo-docs-ru.git
cd fogo-docs-ru
npm install
npm run serve
```

---

<div align="center">

**Made with ❤️ for the Fogo Russian Community**

[Documentation](SETUP.md) • [Quick Start](QUICKSTART.md) • [Contribute](CONTRIBUTING.md) • [License](LICENSE)

</div>

