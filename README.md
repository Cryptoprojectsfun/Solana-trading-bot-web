# Solana Trading Bot Web Interface

A modern web interface for managing Solana trading strategies, liquidity, and token operations.

## Features

- Pump Orders: Create automated buy/sell orders
- Market Making (AMM): Maintain liquidity with custom spread settings
- Anti-Dump Protection: Prevent sharp price drops
- Wallet Management: Create and manage multiple Solana wallets
- Mass Drops: Distribute tokens in batches
- Settings: Configure RPC endpoints and notifications

## Setup

1. Install dependencies:
```bash
npm install
```

2. Install required UI components:
```bash
npx shadcn-ui@latest init
npx shadcn-ui@latest add card tabs button input label alert
```

3. Start the development server:
```bash
npm run dev
```

## Required Dependencies

- @solana/web3.js
- @solana/wallet-adapter-react
- shadcn/ui components
- Lucide React icons

## Configuration

1. Set up your Solana RPC endpoint in the settings
2. Configure your Telegram bot token for notifications
3. Connect your Solana wallet to start trading

## Contributing

Feel free to submit issues and pull requests.

## License

MIT
