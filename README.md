# CoinConnect

A modern web3 wallet connection interface built with React, TypeScript, and Vite.

## Features

- 🔗 Web3 wallet integration
- 🌙 Dark/Light mode support
- 🎨 Modern UI with shadcn/ui components
- ⚡ Built with Vite for fast development
- 🔒 Type-safe with TypeScript
- 💅 Styled with Tailwind CSS

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- ethers.js
- Coinbase Wallet SDK

## Getting Started

### Prerequisites

- Node.js 20 or later
- npm or your preferred package manager

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/coinconnect.git
cd coinconnect
```

2. Install dependencies (If you are using Devcontainer, you can skip this step) and Run the development server. The app will be available at http://localhost:5173:

```bash
npm install
npm run dev
```

### Building for Production

```bash
npm run build
npm run preview
```

## Project Structure

```
src/
├── components/
│   ├── NetworkSelector.tsx
│   ├── WalletConnectButton.tsx
│   └── ...
├── lib/
│   ├── hooks/
│   │   ├── useCoinbaseWallet.ts
│   │   └── ...
│   └── utils/
│       └── ...
```

## License

MIT License - see LICENSE file for details
