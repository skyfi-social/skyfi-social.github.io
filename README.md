# Skyfi - Connecting crypto communities on Bluesky (ATProto)

This repository hosts two different sites for the skyfi ecosystem:

## 🚀 About Skyfi

Skyfi is a fork of the Bluesky client that allows users to:
- Connect Solana and Ethereum wallets to their Bluesky profile
- Enjoy enhanced social networking with features that leverage a client with a builtin wallet.

Our goal is to attract and inspire developers to bring new ideas to the AT Protocol ecosystem. If you are a designer or a developers, bring your ideas and PRs.

## 🌐 Sites

### 1. skyfi.social (Landing Page)
- **Location**: `./skyfi.social/` directory
- **URL**: [skyfi.social](https://skyfi.social)
- **Deployment**: Automatic on any changes to `skyfi.social/` directory

### 2. app.skyfi.social (Web Application)
- **Source**: `skyfi-social/social-app` repository
- **URL**: [app.skyfi.social](https://app.skyfi.social)
- **Deployment**: via Cloudflare

## 🛠️ Development

### Web App (app.skyfi.social)
Built from the `skyfi-social/social-app` repository (Bluesky fork). Our goal is to stay up-to-date with the Blueskay changes to main. We will periodically merge in changes from `main`. (In the early days prior to others working on this project we are using rebase to accomplish this.)

2. Run the "Deploy app.skyfi.social" workflow
3. Specify the branch to deploy (default: "skyfi")

The workflow will:
- Clone the [`skyfi-social/social-app`](https://github.com/skyfi-social/social-app) repo
- Checkout the `skyfi` branch.
- Create a branch with your cool idea. `git checkout -b yourname/cool-idea`
- Install dependencies with `yarn`
- Build the web app with `yarn build-web`
- You should be able to use it by visiting `http://127.0.0.1:19006`
- Commit and push your changes, then submit a PR

#### Deployment
1. The `skyfi` branch is automatically deployed via Cloudflare

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

## 🔗 Links

- **Live App**: [app.skyfi.social](https://app.skyfi.social)
- **Skyfi App Rep**: [github.com/skyfi-social](https://github.com/skyfi-social/social-app)
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
