# MONABLOCK - Blockchain Space Game

A blockchain-powered space arcade game built on Monad Testnet using Multisynq integration. Defeat purple hedgehog obstacles, collect power-ups, and mint NFTs of your achievements!

## Features

- 🎮 **Arcade-style gameplay** with explosion effects and ice crystal power-ups
- 🔗 **Blockchain integration** with Monad Testnet
- 🎨 **NFT minting** for high scores and achievements
- ❄️ **Ice crystal mechanics** that freeze obstacles for 5 seconds
- 💥 **Explosion effects** when shooting obstacles
- 🏆 **Leaderboard system** powered by Multisynq
- 🎯 **Progressive difficulty** with boss obstacles

## Game Controls

- **Arrow Keys**: Move your ship
- **Spacebar**: Shoot bullets
- **R**: Restart game (when game over)
- **M**: Mint Score NFT (when available)
- **P**: Preview NFT design (when available)

## Power-ups

- 🟢 **Green**: Multi-shot (fire 3 bullets)
- 🟣 **Purple**: Rapid-fire (faster shooting)
- 🟡 **Gold**: Clear all obstacles
- 🔵 **Light Blue**: Ice crystal (freeze all obstacles for 5 seconds)

## Getting Started

### Prerequisites

- Node.js 18+ 
- MetaMask wallet
- Monad Testnet setup (Chain ID: 10143)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd monablock
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser

### Wallet Setup

1. Install MetaMask browser extension
2. Add Monad Testnet network:
   - Chain ID: 10143
   - RPC URL: https://testnet-rpc.monad.xyz
   - Currency: MON
3. Connect your wallet to start playing

## Blockchain Features

- **Score Recording**: All game scores are recorded on Monad Testnet
- **NFT Minting**: Mint unique NFTs showcasing your achievements
- **Leaderboard**: Compete with other players globally
- **Reward System**: Earn rewards for high scores

## Technology Stack

- **Frontend**: Next.js 14, React, TypeScript
- **Styling**: Tailwind CSS
- **Blockchain**: Monad Testnet
- **Integration**: Multisynq API
- **Wallet**: MetaMask integration

## Development

### Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint
npm run type-check   # Run TypeScript checks
```

### Project Structure

```
src/
├── app/                 # Next.js app directory
├── components/          # React components
│   ├── GameCanvas.tsx   # Main game component
│   ├── Leaderboard.tsx  # Leaderboard display
│   └── ui/             # UI components
├── lib/                # Utility libraries
│   └── blockchain.ts   # Blockchain integration
└── hooks/              # Custom React hooks
```

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically with zero configuration

### Manual Deployment

1. Build the project:
```bash
npm run build
```

2. Deploy the `out` directory to your hosting provider

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## License

This project is licensed under the MIT License.

## Powered by Multisynq

This game uses Multisynq for blockchain integration and leaderboard management.
