# NFT Marketplace - Solana

A full-stack NFT marketplace built on Solana blockchain in 5 days with a team of 3 developers.

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Rust 1.70+
- Solana CLI 1.16+
- Anchor CLI 0.28+
- Docker Desktop (for MongoDB)

### Setup (Windows)
```powershell
# Run the automated setup script
./scripts/setup.ps1
```

### Setup (Linux/Mac)
```bash
# Make setup script executable and run
chmod +x scripts/setup.sh
./scripts/setup.sh
```

### Manual Development Setup
```bash
# Start MongoDB
docker-compose up -d

# Terminal 1: Smart Contracts
cd smart-contracts
anchor build
anchor deploy

# Terminal 2: Backend  
cd backend
npm install
npm run dev

# Terminal 3: Frontend
cd frontend
npm install
npm run dev
```

## 📁 Project Structure

```
TokenTrio_Solana_Camp_2025/
├── smart-contracts/     # Blockchain Developer (Anchor/Rust)
├── frontend/           # Frontend Developer (Next.js/React)  
├── backend/           # Full-stack Developer (Express/Node.js)
├── shared/           # Common types and utilities
├── docs/            # Documentation
├── scripts/         # Setup and deployment scripts
└── tests/          # Integration tests
```

## 👥 Team Workflow (5 Days)

### Day 1: Foundation
- **Blockchain Dev**: Setup Anchor + basic NFT program
- **Frontend Dev**: Next.js + Wallet integration
- **Full-stack Dev**: Express API + MongoDB

### Day 2: Core Features
- **Blockchain Dev**: Marketplace smart contract
- **Frontend Dev**: NFT display + mint UI
- **Full-stack Dev**: IPFS integration + APIs

### Day 3: Integration & Polish
- **All Team**: Connect frontend to smart contracts
- Polish UI/UX and user experience
- Testing and bug fixes

### Day 4: Testing & Deployment
- Comprehensive testing and optimization
- Production deployment preparation
- Documentation

### Day 5: Launch
- Final testing and polish
- Documentation completion
- Public launch and demo

## ⚡ Tech Stack

### Blockchain
- **Solana** - High-performance blockchain
- **Anchor** - Rust framework for Solana programs
- **Metaplex** - NFT standards and tools

### Frontend
- **Next.js 14** - React framework with App Router
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first styling
- **Solana Wallet Adapter** - Wallet connections

### Backend
- **Node.js** - JavaScript runtime
- **Express** - Web framework
- **MongoDB** - NoSQL database
- **IPFS** - Decentralized storage

## 🎯 MVP Features (5 Days)

### Core Features ✅
1. **NFT Minting** - Upload image → Create metadata → Mint on Solana
2. **Marketplace** - List NFTs for sale with fixed price
3. **Purchase** - Buy NFTs directly with SOL
4. **Wallet Integration** - Connect/disconnect Solana wallets
5. **User Dashboard** - View owned NFTs and active listings

### Technical Features ✅
- Responsive web design
- Real-time transaction status
- Error handling and user feedback
- Basic search and filtering
- Collection support

## 🔗 Development URLs

- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:3001
- **MongoDB**: mongodb://localhost:27017
- **Solana Explorer**: https://explorer.solana.com/?cluster=devnet

## 📋 Daily Standups

### Morning (9:00 AM)
1. What did you complete yesterday?
2. What will you work on today?
3. Any blockers or help needed?
4. Integration points for today?

### Evening (6:00 PM)  
1. Demo working features
2. Plan tomorrow's tasks
3. Risk assessment
4. Cross-team support needed?

## 🎯 Success Metrics

### Technical KPIs
- [ ] NFT minting success rate >95%
- [ ] Transaction completion <30 seconds
- [ ] Page load time <3 seconds
- [ ] Zero critical bugs

### Business KPIs
- [ ] 10+ NFTs minted on launch day
- [ ] 5+ successful trades
- [ ] 20+ wallet connections
- [ ] Positive community feedback

## 🚀 Post-Launch Roadmap

### Week 1-2: Stabilization
- Bug fixes and optimizations
- User feedback implementation
- Performance improvements

### Week 3-4: Enhanced Features
- Auction system
- Advanced collection features
- Mobile optimization

### Month 2+: Growth
- Cross-chain support
- DeFi integrations
- Mobile app
- Enterprise features

## 📚 Documentation

- [Project Structure](./PROJECT_STRUCTURE.md) - Detailed folder organization
- [Roadmap](./ROADMAP_NFT_MARKETPLACE.md) - Complete development roadmap
- [Setup Guide](./docs/SETUP.md) - Detailed setup instructions
- [API Documentation](./docs/API.md) - Backend API reference
- [Smart Contracts](./docs/SMART_CONTRACTS.md) - Blockchain documentation

## 🛠️ Available Scripts

### Smart Contracts
```bash
cd smart-contracts
anchor build      # Build programs
anchor deploy     # Deploy to devnet  
anchor test       # Run tests
```

### Backend
```bash
cd backend
npm run dev       # Development server
npm run build     # Build for production
npm test         # Run tests
```

### Frontend
```bash
cd frontend  
npm run dev       # Development server
npm run build     # Build for production
npm run start     # Production server
```

## 🤝 Contributing

1. Follow the 5-day roadmap strictly
2. Use daily standups for coordination
3. Test integrations daily
4. Document as you build
5. Focus on MVP features only

## 📄 License

MIT License - Built for Solana Camp 2025

---

**Built with ❤️ by TokenTrio Team**