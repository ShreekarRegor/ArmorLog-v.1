# ArmorLog v2.0

A **blockchain-secured defense monitoring system** that logs mission events, anomalies, and threats using smart contracts.
The frontend provides a tactical dashboard while the backend records immutable logs on the blockchain.

---

# Tech Stack

### Blockchain

* Solidity
* Truffle Framework
* Ganache (Local Ethereum Blockchain)

### Frontend

* React (Vite)
* Tailwind CSS
* Ethers.js

### Wallet Integration

* MetaMask

---

# Prerequisites

Make sure the following tools are installed before running the project.

### 1. Install Node.js

Download and install Node.js:

https://nodejs.org/

Check installation:

```
node -v
npm -v
```

---

### 2. Install Ganache

Ganache provides a **local Ethereum blockchain for testing**.

Download from:

https://trufflesuite.com/ganache/

After installing:

* Start Ganache
* Create a workspace
* Default network ID should be:

```
5777
```

---

### 3. Install Truffle Framework

Install Truffle globally:

```
npm install -g truffle
```

Verify installation:

```
truffle version
```

---

### 4. Install MetaMask

Install the MetaMask browser extension:

https://metamask.io/

Steps:

1. Create or import a wallet
2. Add a new network

Use Ganache RPC details:

```
Network Name: Ganache
RPC URL: http://127.0.0.1:7545
Chain ID: 1337
Currency: ETH
```

Import one of the Ganache accounts using its **private key**.

---

# Project Setup

Clone the repository:

```
git clone <repo-url>
cd Armor-Log
```

---

# Install Dependencies

### Backend Dependencies

Inside the main project folder:

```
npm install
```

---

### Frontend Dependencies

Move into the frontend folder:

```
cd armorlog-frontend
npm install
```

Install required frontend libraries:

```
npm install ethers
```

Install Tailwind CSS (v3):

```
npm install -D tailwindcss@3 postcss autoprefixer
npx tailwindcss init -p
```

---

# Compile Smart Contracts

From the root directory:

```
truffle compile
```

---

# Deploy Smart Contracts

Make sure **Ganache is running**.

Then run:

```
truffle migrate --network development
```

This deploys the smart contract and updates the build artifacts.

---

# Start the Frontend

Navigate to the frontend folder:

```
cd armorlog-frontend
npm run dev
```

Open the app in the browser:

```
http://localhost:5173
```

---

# Connecting to Blockchain

1. Click **Connect Wallet**
2. Approve the MetaMask request
3. Ensure MetaMask is connected to the **Ganache network**

Once connected, the dashboard can log events directly to the blockchain.

---

# Project Structure

```
Armor-Log
│
├── contracts
│   └── DefenseSystem.sol
│
├── migrations
│   └── deployment scripts
│
├── build/contracts
│   └── compiled smart contract artifacts
│
├── armorlog-frontend
│   ├── src
│   │   ├── components
│   │   ├── utils
│   │   ├── App.jsx
│   │   └── ArmorLogHome.jsx
│   │
│   └── Tailwind + React UI
│
└── backend
    └── server logic
```

---

# Key Features

* Immutable logging using smart contracts
* Real-time tactical dashboard
* Secure MetaMask authentication
* Blockchain-verified activity feed
* Simulated AI threat detection

---

# Branch Information

```
main
```

Original ArmorLog version.

```
ArmorLog-v2.0
```

Blockchain-enhanced implementation with smart contracts and Web3 integration.

---

# License

MIT License
