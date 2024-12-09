# Reimagine-Truth-Airdrop

Reimagine Truth Airdrop Repository is the core system for managing the $RTO token airdrop. It features smart contracts, automated scripts, frontend and backend tools, and detailed documentation. Designed to reward early supporters, boost engagement, and ensure transparent distribution, it powers the Reimagine Truth community growth.

The Reimagine Truth airdrop is designed to reward early supporters, NFT buyers, and community members while driving engagement and participation in the project. The plan ensures a fair distribution of the $RTO tokens and incentivizes the growth of the Reimagine Truth ecosystem.

---

## 🏆 **Airdrop Goals**

- **Reward Early Supporters:** Offer incentives to the first adopters of the Truth Seekers Deck NFTs.
- **Build Community Engagement:** Attract new members to join our Telegram group, follow on Twitter, and interact with our ecosystem.
- **Drive Awareness:** Use the airdrop to generate buzz about the project ahead of the official token launch.
- **Encourage Marketplace Activity:** Incentivize activity such as NFT purchases and auctions.

---

## 🚀 **Airdrop Phases**

1. **Early NFT Buyers**
   - **Eligibility:** Purchase Truth Seekers Deck NFTs before the $RTO token launch.
   - **Reward:** 10% of the airdrop pool.
   - **Snapshot Date:** December 24, 2024.

2. **Community Engagement**
   - **Eligibility:** Complete tasks like joining Telegram, following on Twitter, and signing up for the newsletter.
   - **Reward:** 15% of the airdrop pool.

3. **Referrals**
   - **Eligibility:** Earn rewards by referring new community members.
   - **Reward:** 5% of the airdrop pool.

4. **General Airdrop for Wallet Holders**
   - **Eligibility:** Open to all Optimism chain wallet holders.
   - **Reward:** 70% of the airdrop pool.

---

## 📊 **Airdrop Token Allocation**

| **Category**          | **Percentage** |
|------------------------|----------------|
| Early NFT Buyers       | 10%            |
| Community Engagement   | 15%            |
| Referrals              | 5%             |
| General Airdrop        | 70%            |
| **Total**              | **100%**       |

---

## 🗓️ **Timeline**

- **Announcement:** December 15, 2024  
- **Snapshot for NFT Holders:** December 24, 2024  
- **Airdrop Distribution:** January 1, 2025  

---

## 🛠️ **Reimagine-Truth-Airdrop-Repository-Structure**

```
Reimagine-Truth-Airdrop/
├── contracts/                 # Smart contracts for token distribution
│   ├── AirdropDistributor.sol # Contract to manage $RTO token airdrops
│   └── Token.sol              # ERC-20 contract for $RTO tokens
│
├── scripts/                   # Scripts for automation
│   ├── generateSnapshot.js    # Script to create a snapshot of eligible wallets
│   ├── distributeTokens.js    # Script to execute token airdrop
│   ├── verifyTasks.js         # Script to verify community engagement tasks
│   └── referralTracker.js     # Script for referral tracking and rewards
│
├── data/                      # Data storage and management
│   ├── snapshot.json          # JSON file containing wallet snapshot data
│   ├── referrals.json         # JSON file storing referral details
│   ├── engagement.csv         # CSV file for community engagement tasks
│   └── README.md              # Notes on data structure
│
├── frontend/                  # Frontend for airdrop management and user interface
│   ├── public/                # Static assets (e.g., images, icons)
│   ├── src/                   # Source files for the frontend app
│   │   ├── components/        # React components for the UI
│   │   ├── pages/             # Pages for the airdrop website
│   │   └── App.js             # Main frontend entry point
│   └── package.json           # Dependencies for the frontend
│
├── backend/                   # Backend logic for managing airdrop data
│   ├── controllers/           # API endpoint handlers
│   ├── models/                # Database models for wallet tracking
│   ├── routes/                # API routes for airdrop tasks
│   ├── services/              # Core logic (e.g., task validation, token distribution)
│   ├── server.js              # Main backend server entry point
│   └── package.json           # Dependencies for the backend
│
├── docs/                      # Documentation for the airdrop process
│   ├── overview.md            # Airdrop overview and goals
│   ├── eligibility.md         # Criteria for airdrop participation
│   ├── tokenomics.md          # Tokenomics of $RTO and airdrop distribution
│   └── setup-guide.md         # Setup instructions for running the repository
│
├── tests/                     # Unit tests for contracts and scripts
│   ├── contracts/             # Tests for smart contracts
│   ├── scripts/               # Tests for distribution scripts
│   └── README.md              # Instructions for running tests
│
├── .env                       # Environment variables (e.g., private keys, API keys)
├── .gitignore                 # Git ignore rules
├── README.md                  # Overview and introduction to the airdrop repository
└── LICENSE                    # License for the repository
```

---

## 🔑 **Key Highlights of the Repository**

### 💼 **Smart Contracts**
- **`AirdropDistributor.sol`**: Handles the distribution logic for $RTO tokens.  
- **`Token.sol`**: ERC-20 token contract for $RTO.  

### ⚙️ **Scripts**
- Automates wallet snapshots, token distribution, task validation, and referral tracking.

### 📂 **Data**
- JSON and CSV files to manage snapshots, referrals, and engagement data.

### 🖥️ **Frontend**
- User-friendly interface for checking eligibility, claiming tokens, and tracking airdrop status.

### 🔗 **Backend**
- API endpoints, database models, and services for secure and efficient token distribution.

### 📄 **Documentation**
- Guides for airdrop participation, setup, and repository contribution.

---

## 🤝 **Get Involved**

Your contributions can help shape the future of Reimagine Truth! Whether you're a developer, designer, or community member, there are many ways to get involved.

---

📜 **License:** This repository is licensed under the [MIT License](LICENSE).

🌐 **Visit Us:** [ReimagineTruth.io](https://reimaginethetruth.io)

🚀 **Join the Movement!**  
