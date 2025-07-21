# Skyfi - Connecting crypto communities on Bluesky (ATProto)

Skyfi is an open source fork of the Bluesky client focused on features for crypto-curious users and crypto natives.

## 🚀 About Skyfi

The goal of Skyfi is to be a platform for crypto-curious users and crypto natives to experiment and build features on AT Protocol. We aim to attract and inspire developers to bring new ideas to the AT Protocol ecosystem. Whether you're a designer or a developer, bring your ideas and PRs.

Skyfi is a fork of the Bluesky client that allows existing Bluesky users to connect Solana and Ethereum wallets to their Bluesky profile. Login uses OAuth to an existing account, and connecting crypto wallets requires a browser-based wallet extension - tested with Phantom, MetaMask, and Brave wallet.

### Roadmap
- Direct and group messaging based on Skyfi's novel use of encrypted messages over SMTP. (In progress)
- Profile updates to display crypto wallet addresses 
- Send USDC to Skyfi users
- Onboard new users with a built-in native wallet

### Advanced Experimental features
In addition to incremental features on the roadmap, we are also experimenting with more advanced crypto-native features.

#### PDS with wallet-based authentication
Once we have native wallet support in the Skyfi client, we can use this wallet to authenticate with the PDS instead of using a password in the PDS.

#### Farcaster FID as new DID

Farcaster has a robust decentralized ID with an excellent balance of self-custody keys and recoverability when self-custody keys are lost. Farcaster IDs are managed on Optimism, an Ethereum L2, making them censorship-resistant. This change would be very experimental because it is not compatible with the AT Protocol unless endorsed by the Bluesky team.

Bring your ideas for enhanced social networking with features that leverage a Bluesky client with a built-in wallet.

## https://skyfi.social

This repository hosts Skyfi.social site on Github Pages.

- **Location**: `./skyfi.social/` directory
- **URL**: [skyfi.social](https://skyfi.social)
- **Deployment**: Automatic on any changes to `skyfi.social/` directory

Built with:
- HTML5
- Custom CSS
- Vanilla JavaScript

### Local Development
1. Navigate to the `skyfi.social` directory
2. Open `index.html` in your browser

### Deployment
Automatically deploys when changes are made to files in the `skyfi.social/` directory.

## Skyfi Web App https://app.skyfi.social
- **Source**: `https://github.com/skyfi-social/social-app` repository
- **URL**: [app.skyfi.social](https://app.skyfi.social)
- **Deployment**: via Cloudflare

## 🛠️ Development

### Prerequisites
- Node.js and yarn
- Browser-based crypto wallet (Phantom, MetaMask, or Brave wallet)

### Web App Development (app.skyfi.social)

The web app is built from the [`skyfi-social/social-app`](https://github.com/skyfi-social/social-app) repository, a fork of the [Bluesky repo](https://github.com/bluesky-social/social-app). Our goal is to stay up-to-date with Bluesky changes on the main branch by periodically merging changes from `main`.

#### Getting Started
1. Clone the [`skyfi-social/social-app`](https://github.com/skyfi-social/social-app) repo
2. Checkout the `skyfi` branch: `git checkout skyfi`
3. Create a feature branch: `git checkout -b yourname/cool-idea`
4. Install dependencies: `yarn install`
5. Start development server: `yarn web`
6. Open `http://127.0.0.1:19006` in your browser
7. Make your changes and test thoroughly
8. Commit and push your changes, then submit a PR

#### Deployment
The `skyfi` branch is automatically deployed to [app.skyfi.social](https://app.skyfi.social) via Cloudflare when changes are merged.


## 🔗 Links

- **Live App**: [app.skyfi.social](https://app.skyfi.social)
- **Skyfi App Repo**: [github.com/skyfi-social/social-app](https://github.com/skyfi-social/social-app)
- **GitHub Organization**: [github.com/skyfi-social](https://github.com/skyfi-social)
- **Website**: [skyfi.social](https://skyfi.social)

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
