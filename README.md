# skyfi - Connecting crypto communities on Bluesky (ATProto)

This repository hosts two different sites for the skyfi ecosystem:

## 🌐 Sites

### 1. skyfi.social (Landing Page)
- **Location**: `./skyfi.social/` directory
- **URL**: [skyfi.social](https://skyfi.social)
- **Deployment**: Automatic on any changes to `skyfi.social/` directory

### 2. app.skyfi.social (Web Application)
- **Source**: `skyfi-social/social-app` repository
- **URL**: [app.skyfi.social](https://app.skyfi.social)
- **Deployment**: Manual via GitHub Actions workflow

## 🚀 About skyfi

Skyfi is a fork Bluesky client that allows users to:
- Connect Solana and Ethereum wallets to their Bluesky profile
- Enjoy enhanced social networking with crypto features

## 🛠️ Development

### Landing Page (skyfi.social)
Built with:
- HTML5
- Custom CSS
- Vanilla JavaScript

#### Local Development
1. Navigate to the `skyfi.social` directory
2. Open `index.html` in your browser

#### Deployment
Automatically deploys when changes are made to files in the `skyfi.social/` directory.

### Web App (app.skyfi.social)
Built from the `skyfi-social/social-app` repository (Bluesky fork).

#### Manual Deployment
1. Go to the Actions tab in GitHub
2. Run the "Deploy app.skyfi.social" workflow
3. Specify the branch to deploy (default: "skyfi")

The workflow will:
- Checkout the specified branch from `skyfi-social/social-app`
- Install dependencies with `yarn`
- Build the web app with `yarn build-web`
- Deploy to GitHub Pages

## 🔗 Links

- **Live App**: [app.skyfi.social](https://app.skyfi.social)
- **GitHub Organization**: [github.com/skyfi-social](https://github.com/skyfi-social)
- **Website**: [skyfi.social](https://skyfi.social)

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).