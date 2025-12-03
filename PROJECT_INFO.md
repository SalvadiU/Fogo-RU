# Fogo Documentation - Russian Translation

This repository contains the complete Russian translation of the [Fogo Community Documentation](https://community-docs.fogo.io).

## About Fogo

Fogo is the fastest SVM-compatible blockchain, built for speed, fairness, and performance. With 40ms block times and 1.3s finality, Fogo delivers a real-time on-chain experience for traders and DeFi users.

## Documentation Structure

```
fogo/
├── README.md                           # Overview (Main page)
├── SUMMARY.md                          # Navigation structure
├── getting-started/
│   ├── README.md                      # Getting Started
│   ├── transferring-to-fogo.md        # Transferring to Fogo
│   └── ecosystem.md                   # Ecosystem overview
├── SETUP.md                           # Setup instructions for GitBook
├── CONTRIBUTING.md                    # Contribution guidelines
└── book.json                          # GitBook configuration
```

## Features

✅ **Complete Translation**: All pages from the original documentation  
✅ **GitBook Ready**: Configured for instant GitBook deployment  
✅ **Maintained Terminology**: Consistent use of technical terms  
✅ **Easy Updates**: Synced with original documentation  
✅ **Community Driven**: Open for contributions

## Pages Included

1. **Overview (README.md)**
   - What is Fogo
   - Why Fogo exists
   - Key features (Sessions, Colocation, Custom Client, Validator Set)
   - Ecosystem overview

2. **Getting Started**
   - Quick start guide
   - Wallet setup
   - Getting $FOGO tokens
   - Using applications

3. **Transferring to Fogo**
   - Portal Bridge guide
   - Cross-chain transfers
   - Security considerations
   - FAQ

4. **Ecosystem**
   - All ecosystem projects (Ambient, Valiant, Pyron, FogoLend, Brasa, FluxBeam, Invariant, Portal Bridge)
   - Use cases for different user types
   - Future roadmap

## Quick Deploy to GitBook

### Method 1: GitHub Integration (Recommended)

1. Fork/clone this repository
2. Push to your GitHub account
3. Go to [GitBook](https://www.gitbook.com)
4. Click "New Space" → "Import from GitHub"
5. Select this repository
6. Done! GitBook will auto-sync

### Method 2: GitBook CLI

```bash
# Install GitBook CLI
npm install -g gitbook-cli

# Navigate to project
cd fogo

# Install plugins
gitbook install

# Preview locally
gitbook serve

# Build static site
gitbook build
```

### Method 3: Direct Import

1. Download this repository as ZIP
2. Go to GitBook → "New Space" → "Import"
3. Upload the ZIP file
4. Configure and publish

## Configuration Files

- **SUMMARY.md**: Navigation structure (sidebar)
- **book.json**: GitBook settings, plugins, and variables
- **.gitbook.yaml**: GitBook sync configuration
- **package.json**: NPM dependencies for local development

## Plugins Included

- `search-pro`: Enhanced search with Russian language support
- `page-toc`: Automatic table of contents for each page
- `back-to-top-button`: Easy navigation
- `expandable-chapters`: Collapsible sidebar sections
- `sharing`: Social media sharing buttons

## Translation Guidelines

### Terminology

| English | Russian | Notes |
|---------|---------|-------|
| Blockchain | Блокчейн | No translation |
| Staking | Стейкинг | Transliteration |
| DeFi | DeFi | Keep as-is |
| Sessions | Сессии | But keep "Fogo Sessions" |
| Colocation | Совместное размещение | With explanation |

**Never translate**: Project names (Ambient, Valiant, Fogo Sessions, etc.)

### Style Guide

- Use formal "вы" instead of informal "ты"
- Maintain consistent terminology throughout
- Preserve original structure and formatting
- Add clarifications when needed for Russian audience

## Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### How to Contribute

1. **Fix typos/errors**: Create a PR directly
2. **Improve translations**: Open an issue to discuss first
3. **Add new content**: Check original site for updates
4. **Update outdated info**: Create an issue with details

## Syncing with Original

Original documentation: https://community-docs.fogo.io

**Sync schedule**:
- Check for updates weekly
- Translate new sections as they appear
- Update changed content
- Track via GitHub Issues

## Development

### Local Preview

```bash
# Install dependencies
npm install

# Serve locally at http://localhost:4000
npm run serve
```

### Build

```bash
# Build static site to _book/
npm run build
```

## Support

- **Original Docs**: https://community-docs.fogo.io
- **Fogo Website**: https://fogo.io
- **GitHub Issues**: Report bugs or request features
- **Community**: Discord / Telegram (Russian channels)

## License

MIT License - see [LICENSE](LICENSE) file

## Acknowledgments

- Fogo team for the original documentation
- All contributors to the Russian translation
- GitBook for the documentation platform

## Status

- ✅ Overview page (README.md)
- ✅ Getting Started
- ✅ Transferring to Fogo
- ✅ Ecosystem
- ✅ GitBook configuration
- ⏳ Additional pages (as they appear on original site)

## Contact

For questions about this translation:
- Open a GitHub Issue
- Join Fogo community channels
- Check [SETUP.md](SETUP.md) for deployment help

---

**Last Updated**: December 2024

**Version**: 1.0.0

**Target Audience**: Russian-speaking Fogo users and developers

