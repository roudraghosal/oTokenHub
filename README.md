# PoolTogether dApp

A modern React dApp for interacting with PoolTogether protocol, featuring MetaMask wallet connection, deposit functionality, odds calculation, leaderboard data from The Graph, and NFT badge minting.

![PoolTogether dApp](https://via.placeholder.com/800x400/1a1a2e/ffffff?text=PoolTogether+dApp)

## 🎯 Features

### 🔗 Wallet Connection
- **MetaMask Integration**: Seamless wallet connection using MetaMask
- **Auto-detection**: Automatically detects existing wallet connections
- **Network Support**: Polygon and Ethereum mainnet support
- **Connection Status**: Visual indicators for connection status

### 💰 Deposit Functionality
- **USDC Deposits**: Deposit USDC tokens to PoolTogether pools
- **Amount Validation**: Real-time input validation and error handling
- **Transaction Flow**: Complete approval → deposit flow
- **Balance Display**: Show current USDC and PoolTogether balances
- **Max Button**: Quick-fill with maximum available balance

### 📊 Odds Calculator
- **Real-time Calculations**: Dynamic odds calculation based on deposit amount
- **Pool Share Visualization**: Visual representation of user's pool percentage
- **Expected APY**: Calculate expected annual percentage yield
- **Winning Probability**: Show probability of winning prizes
- **Risk Information**: Display no-loss protocol benefits

### 📈 Leaderboard
- **Top Winners**: Display users with most prize wins
- **Biggest Deposits**: Show largest recent deposits
- **Consistent Players**: Highlight most frequent depositors
- **The Graph Integration**: Fetch real-time data from PoolTogether subgraph
- **Interactive Tabs**: Switch between different leaderboard views

### 🎖️ NFT Badge System
- **ERC721 Contract**: Custom smart contract for minting badges
- **Multiple Badge Types**: 
  - First Deposit Badge
  - High Roller Badge (>$1000 deposit)
  - Consistent Player Badge (10+ deposits)
  - Lucky Winner Badge (won a prize)
- **Auto-minting**: Automatic badge minting based on user actions
- **Badge Gallery**: View earned and available badges
- **Rarity System**: Different rarity levels for badges

### 🎨 UI/UX Features
- **Responsive Design**: Mobile-first design approach
- **TailwindCSS**: Modern styling with utility classes
- **Glassmorphism**: Beautiful backdrop blur effects
- **Animations**: Smooth transitions and loading states
- **Dark Theme**: Elegant dark theme with gradient backgrounds
- **Interactive Elements**: Hover effects and micro-interactions

## 🛠️ Technology Stack

### Frontend
- **Next.js 15**: React framework with App Router
- **TypeScript**: Type-safe development
- **TailwindCSS**: Utility-first CSS framework
- **React Hooks**: Modern React patterns

### Blockchain
- **Ethers.js v5**: Ethereum interaction library
- **MetaMask**: Wallet connection and transaction signing
- **ERC721**: NFT standard for badges
- **Polygon Network**: Primary deployment network

### Data
- **The Graph**: Decentralized indexing protocol
- **Apollo Client**: GraphQL client for data fetching
- **Real-time Updates**: Live leaderboard data

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ installed
- MetaMask browser extension
- Git for version control

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/pooltogether-dapp.git
cd pooltogether-dapp
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev
```

4. **Open in browser**
Navigate to `http://localhost:3000`

## 📱 Usage Guide

### 1. Connect Wallet
- Click "Connect Wallet" button
- Approve MetaMask connection
- Ensure you're on Polygon network

### 2. Deposit USDC
- Enter deposit amount in USDC
- Click "Deposit & Enter Pool"
- Approve USDC spending in MetaMask
- Confirm deposit transaction
- Receive NFT badge automatically

### 3. View Odds
- See your winning probability
- Check expected APY
- View pool share percentage
- Understand no-loss benefits

### 4. Check Leaderboard
- Browse top winners
- See biggest deposits
- Find consistent players
- Real-time data updates

### 5. Collect NFT Badges
- Earn badges through deposits
- View badge collection
- Mint additional badges
- Check badge rarity

---

**Built with ❤️ for the DeFi community**
