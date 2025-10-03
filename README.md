# Qubihub Platform Proposal

## Introduction

Qubihub is a comprehensive, all-in-one platform for interacting with the Qubic network. Inspired by Polkadot.js Apps and Qforge, Qubihub combines a full-featured blockchain explorer, smart contract tools, and developer utilities into a single, user-friendly interface. This platform serves as the central hub for the Qubic ecosystem, providing essential tools for developers, users, and stakeholders.

**Funding Request:** $18,000 USD  
**Destination Wallet:** `QZLVZPWQGEBXWDCRMYOTVQDQEQCBFOKTPNRNMHGEYDUNFLHRBSXTEOKEZUAC`

---

## Key Features

- **Enhanced Blockchain Explorer** – Browse ticks, transactions, accounts, and network statistics with detailed transaction logs
- **Advanced Smart Contract Tools** – Interact with Qubic smart contracts, test transactions, and query contract state
- **Comprehensive Contract Parser** – Dynamical analyze of Qubic smart contracts
- **Wallet Integration** – Connect and manage Qubic wallets with WalletConnect support
- **Address Book** – Manage frequently used addresses with aliases
- **Governance Tools** – General Quorum proposal, CCF proposal create/vote(Considering integration)
- **IPO Integration** - (Considering integration)
- **Developer Utilities** – Essential tools for Qubic development

---

## Solutions Offered by Qubihub

- **Fragmented Ecosystem**  
  → Qubihub consolidates important Qubic tools into a single, unified platform

- **Developer Onboarding**  
  → Offers intuitive interface for both technical and non-technical users

- **Network Transparency**  
  → Enhanced blockchain explorer with detailed transaction analysis

- **Ecosystem Growth**  
  → Lowers barriers to entry and encourages Qubic adoption

---

## Components to Be Developed

### Core Platform Features
- **Blockchain Explorer**
  - Transaction browsing and analysis
  - Account information and balances
  - Network statistics and metrics
  - Detailed transaction logs
  - Support switch of mainnet/testnet by RPC endpoints

- **Contract Parser**
  - Automatic contract analysis
  - Function and struct extraction
  - Contract registry management

- **Smart Contract Interface**
  - Dynamic parse of structs, inputs, outputs, logs of smart contract
  - Query and submit transaction to smart contract
  - Contract source code analysis
  - Support switch of mainnet/testnet by github link

- **Wallet Management**
  - WalletConnect integration
  - Account management
  - Manange QUBIC and Assets, Qubicbay NFTs

- **Governance Tools** (Considering)
  - General quorum proposal/CCF proposal creation and voting
  - IPO

- **Developer Tools**
  - Transaction Encoder/Decoder
  - Contract testing environment
  - Transaction simulation
  - Basic string/decimal/binary converters for Qubic
  - Hex parser by C++ struct

> [!NOTE]     
> **Contract Parser** doesn't have any interface, it will just integrate into explorer and smart contract interface

> [!NOTE]   
> **Governance Tools** are under considering. After getting feedback from community, it will be determined to be integrated.

---

## Milestones and Deliverables

### Milestone 1 – Construct POC version
- ✅ Wallet connect
- ✅ Qubic network metrics, statistics
- ✅ Browsing Richlist & Computor
- ✅ Transaction browsing and analysis

> [!NOTE]
> Development is already started and Milestone 1 is in final stage.

### Milestone 2 – UI/UX upgrade & Dynamic contract parser & Smart Contract Interaction Tools
- ✅ UI/UX improve
- ✅ Contract interaction interface
- ✅ Function calling and querying
- ✅ Contract source code analyze
- ✅ Dynamic contract parser implementation

### Milestone 3 – Developer console & AddressBook & Improved Wallet management
- ✅ Developer console
- ✅ Browsing all user assets in wallet and managing them - QUBIC, Assets, Qubicbay NFT
- ✅ Address book functionality
- ✅ Customize Qubihub UI & Working behaviour using settings

### Milestone 4 – Governance
- ✅ Governance proposal creation and voting
- ✅ Integrating crucial 3rd party apps like Qearn, QX, Qvault (Negotiable)
- ✅ Performance optimization and testing

---

## Payment Terms

**Total Request:** $18,000 USD

**Breakdown:**
- Development: 360 hours = $16,200
- Design & UX: 50 hours = $1,500
- Infrastructure & Deployment: $500

**Disbursement:**
- M1 – 20% ($3,600)
- M2 – 25% ($4,500)
- M3 – 25% ($4,500)
- M4 – 30% ($4,500)

---

## Team Composition

- **SerendipitySeeker** – Lead Developer & Project Manager
  - **Github**: https://github.com/serendipity-seeker
  - Contributor of several Qubic projects like Qwallet, Qearn, QubiPy, Qxboard, QubicBay
- **UI/UX Designer**

**Additional Support:**
- Community contributors for testing and feedback
- Qubic ecosystem developers for integration support

---

## Conclusion

Qubihub represents a critical infrastructure project for the Qubic ecosystem. By providing a comprehensive, user-friendly platform that consolidates essential tools and features, Qubihub will significantly lower barriers to entry, encourage adoption, and accelerate ecosystem growth. The platform's focus on developer tools, user experience, and community engagement positions it as a cornerstone of the Qubic ecosystem.

## Motivation
While working in Qubic Ecosystem, I felt lack of developer utilities like Polkadot.js App in Qubic ecosystem. Especially working in integration with smart contract, it was very difficult to analyze smart contract transactions and detailed internal state changes. So I always used my own script collection, cli collection for interacting with smart contract. I was looking forward to new project like Polkadot.js App in Qubic, finally Qforge came out, provided rich experience in smart contract test. But while development and supporting QubicBay tickets, I still felt bad experience of transaction analyze, especially Qubic official explorer was not enough for smart contract interaction, it took so much time to get all necessary info using different tools, different APIs. So I decided to build my own tool, so built Qubihub POC version quickly. It helped me so much in QubicBay development and maintanence. I want to continue building of Qubihub and finish it with the help of incubation.

> [!NOTE]
> After complete POC version, it will be public repository, welcome to any PR, issues, feedbacks.   
> I want this project is advancing as community-driven project. 💖