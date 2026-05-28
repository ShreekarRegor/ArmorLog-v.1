# ArmorLog – Blockchain Based Defense Logging System

ArmorLog is a blockchain-based defense logging system designed to securely store and monitor sensitive mission records and activity logs. The platform focuses on data integrity, tamper-proof storage, and intelligent activity monitoring using blockchain and AI-based tools.

The project combines smart contracts, real-time databases, AI integrations, and secure authentication to create a modern defense-oriented logging platform.

---

# Features

- Blockchain-based secure logging system
- Tamper-proof mission record storage
- Smart contract integration using Solidity
- Real-time alert generation
- Firebase authentication and database integration
- AI-powered activity detection
- Secure transaction handling with MetaMask
- Responsive and modern user interface

---

# Tech Stack

## Frontend
- React.js
- Tailwind CSS
- JavaScript

## Backend & Blockchain
- Solidity
- MetaMask
- Firebase

## AI & Detection
- OpenCV
- SpaCy

## Tools
- Git & GitHub
- VS Code

---

# Project Structure

```bash
ArmorLog-v.1-main/
│
├── client/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── assets/
│
├── smart-contracts/
│   ├── Solidity contracts
│   └── deployment scripts
│
├── firebase/
│
└── README.md
```

---

# Smart Contract Example

```solidity
pragma solidity ^0.8.0;

contract MissionLog {
    string[] public logs;

    function addLog(string memory _log) public {
        logs.push(_log);
    }
}
```

---

# Firebase Authentication Example

```javascript
const loginUser = async (email, password) => {
  await signInWithEmailAndPassword(auth, email, password);
};
```

---

# AI Detection Example

```python
import cv2

camera = cv2.VideoCapture(0)
ret, frame = camera.read()
```

---

# Installation & Setup

## Clone Repository

```bash
git clone <repository-link>
```

## Navigate to Project Folder

```bash
cd ArmorLog-v.1-main
```

## Install Dependencies

```bash
npm install
```

## Start Development Server

```bash
npm run dev
```

---

# Key Learning Outcomes

- Blockchain and smart contract development
- Firebase authentication and real-time database integration
- AI-based activity detection using OpenCV and SpaCy
- Frontend-backend integration
- Debugging transaction and authentication workflows
- Secure data handling and workflow optimization

---

# Future Enhancements

- Advanced AI threat detection
- Multi-user role-based access
- Cloud deployment
- End-to-end encrypted communication
- Real-time analytics dashboard
- Automated anomaly detection system

# License

This project is created for educational and learning purposes.
