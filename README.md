# nftSub - Subscription NFT Platform

A decentralized subscription management platform built on Ethereum and Reactive Network, enabling NFT-based recurring payments and subscription services.

## 🏗️ Project Structure

```
nftSub/
├── nftSub-contracts/     # Smart contracts for subscription management
├── nftSub-sdk/          # TypeScript SDK for integrating subscriptions
└── nftSub-frontend/     # React frontend application
```

## 📦 Components

### [Smart Contracts](./nftSub-contracts/)
Core smart contracts implementing subscription logic with Reactive Network integration for automated payments.

- **SubscriptionNFT**: ERC-721 NFT representing subscriptions
- **SubscriptionManager**: Manages subscription lifecycle and payments
- **SubscriptionReactive**: Handles automated recurring payments via Reactive Network

[View Contracts Documentation →](./nftSub-contracts/README.md)

### [SDK](./nftSub-sdk/)
TypeScript SDK providing easy integration with the subscription platform.

- React hooks for subscription management
- UI components for quick integration
- Full TypeScript support
- Comprehensive testing suite

[View SDK Documentation →](./nftSub-sdk/README.md)

### [Frontend](./nftSub-frontend/)
Modern React application showcasing the subscription platform.

- Next.js 14 with App Router
- Tailwind CSS for styling
- RainbowKit for wallet connection
- Real-time subscription management

[View Frontend Documentation →](./nftSub-frontend/README.md)

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- pnpm
- Ethereum wallet (MetaMask recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/nftSub.git
cd nftSub
```

2. Install dependencies:
```bash
# Install contract dependencies
cd nftSub-contracts
pnpm install

# Install SDK dependencies
cd ../nftSub-sdk
pnpm install

# Install frontend dependencies
cd ../nftSub-frontend
pnpm install
```

3. Set up environment variables:
```bash
# In nftSub-contracts/
cp .env.example .env

# In nftSub-frontend/
cp .env.example .env.local
```

4. Deploy contracts (optional for local development):
```bash
cd nftSub-contracts
pnpm run deploy:local
```

5. Start the frontend:
```bash
cd nftSub-frontend
pnpm run dev
```

## 🌐 Deployments

### Sepolia Testnet
- SubscriptionNFT: `0x...` 
- SubscriptionManager: `0x...`
- SubscriptionReactive: `0x...`

[View all deployments →](./nftSub-contracts/deployments/)

## 📖 Documentation

- [Architecture Overview](./nftSub-contracts/ARCHITECTURE.md)
- [SDK Integration Guide](./nftSub-sdk/README.md)
- [Frontend Development](./nftSub-frontend/README.md)
- [Deployment Guide](./nftSub-contracts/DEPLOYMENT.md)

## 🧪 Testing

```bash
# Test contracts
cd nftSub-contracts
pnpm test

# Test SDK
cd nftSub-sdk
pnpm test

# Test frontend
cd nftSub-frontend
pnpm test
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](./CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## 🔗 Links

- [Website](https://nftsub.io)
- [Documentation](https://docs.nftsub.io)
- [Twitter](https://twitter.com/nftsub)
- [Discord](https://discord.gg/nftsub)

## 💡 Built With

- [Ethereum](https://ethereum.org/)
- [Reactive Network](https://reactive.network/)
- [OpenZeppelin](https://openzeppelin.com/)
- [React](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [RainbowKit](https://rainbowkit.com/)
- [Viem](https://viem.sh/)
- [Wagmi](https://wagmi.sh/)