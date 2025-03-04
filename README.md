**Blockchain-Based Voting System for Corporate Governance (BBVS-CG)**

[(https://opensource.org/licenses/MIT)]

  A decentralized voting system leveraging Ethereum blockchain and smart contracts to enhance transparency, security, and accessibility in corporate governance. Designed to prevent fraud, ensure voter privacy, and automate compliance through immutable records and AI-driven analytics.

## 📋 Overview

  BBVS-CG provides a secure, transparent, and efficient platform for corporate voting processes. By utilizing blockchain technology, it ensures that all votes are immutable, verifiable, and resistant to tampering, while maintaining voter privacy through advanced cryptographic techniques.

## ✨ Features

- **Immutable Voting Records**: All votes are stored on the Ethereum blockchain, creating a tamper-proof audit trail
- **Smart Contract Automation**: Self-executing contracts handle vote tallying and enforce governance rules
- **AI-Driven Fraud Detection**: Real-time anomaly monitoring ensures election security
- **User-Friendly GUI**: Intuitive dashboard interfaces for voters, administrators, and regulators
- **Regulatory Compliance**: Automated reporting aligned with SEC, SEBI, and RBI standards


## 🛠️ Technology Stack

- **Blockchain**: Ethereum (Solidity, Truffle, Ganache)
- **Frontend**: React.js, Bootstrap, Web3.js
- **Backend**: Node.js
- **Security**: Zero-Knowledge Proofs (ZKPs), Metamask Wallet Integration
- **AI/ML**: Fraud detection models (Python/TensorFlow)
- **Storage**: IPFS (InterPlanetary File System)


## 📦 Prerequisites

1. [Node.js](https://nodejs.org/) (v18+)
2. [Ganache](https://trufflesuite.com/ganache/) (Ethereum test network)
3. [Metamask](https://metamask.io/) browser extension (Chrome recommended)


## 🚀 Installation

1. Clone the repository:

```
git clone https://github.com/raj-pate1/BVS.git
cd E-Voting_System_Blockchain
```


2. Install dependencies:

```
npm install
```


3. Compile smart contracts:

```
truffle compile
```


4. Deploy to local blockchain:

```
truffle migrate --reset
```


5. Start the application:

```
npm start
```


## ⚙️ Configuration

### Connect Metamask to Ganache:

1. Open Ganache and start a local Ethereum network (Quick Start)
2. In Metamask, go to Settings > Networks > Add Network

1. Network Name: Local Ganache
2. New RPC URL: Use the RPC URL from Ganache (default: [http://localhost:7545](http://localhost:7545))
3. Chain ID: 1337
4. Currency Symbol: ETH





### Import Ganache Account to Metamask:

1. In Ganache, click the 🔑 icon next to an account to view its private key
2. In Metamask, go to Import Account and paste the private key


## 📱 Usage

### Voter Dashboard

- Cast votes securely via the React-based interface
- View real-time results and audit trails


### Admin Panel

- Manage proposals and voting sessions
- Monitor compliance alerts and AI-generated fraud reports


### Regulator Access

- Audit immutable voting records on the blockchain
- Generate compliance reports for regulatory bodies


## 🔍 System Architecture

  ![image](https://github.com/user-attachments/assets/14272e41-5c61-415c-a89b-e829e6708d61)


## 👥 Contributors

- Patil Tejas Dinesh (2203051260006)
- Sable Krishna Sable (2203051260042)
- Patil Himanshu Chandrakant (2203051269002)
- Shruti Sharma (2203051260058)


## 🧑‍🏫 Project Guidance

Guided by Mr. Gautam Singh, Assistant Professor (CSE/IT), Parul University.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## 📞 Contact

For questions or feedback, please open an issue in the GitHub repository.
