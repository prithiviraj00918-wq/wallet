# 💳 CryptoPulse – Smart Web3 Wallet Dashboard

CryptoPulse is a modern Web3 wallet dashboard that allows users to securely connect their MetaMask wallet, view real-time ETH balance, and check recent transactions through a premium glassmorphism UI.

---

## Features

-  MetaMask wallet connection
-  Live Ethereum balance display
-  Recent transaction history
-  Glassmorphism UI with HD crypto background
-  No backend required

---

## Tech Stack

- HTML5  
- CSS3 (Glassmorphism UI)  
- JavaScript (ES6)  
- Ethers.js v6  
- Blockscout Public API  
- MetaMask

---

## Project Structure

CryptoPulse/
├── index.html
└── README.md

---

## How to Run

1. Install MetaMask browser extension  
2. Open `index.html` in a modern browser  
3. Click **Connect** to link your wallet  
4. Click **Balance** or **Transactions** to view details  

No server or backend setup required.

---

## How It Works

- Uses `ethers.BrowserProvider` to connect MetaMask
- Retrieves wallet address via signer
- Fetches ETH balance from Ethereum network
- Loads transaction history from Blockscout API
- Displays data in a responsive dashboard UI

---

## Notes

- Works on Ethereum Mainnet
- If no transactions exist, it displays “No transactions found”
- Public APIs may have rate limits

---

## Security Disclaimer

This project is for educational and portfolio purposes only.  
Do not use it to manage real funds or expose private keys.

---

## License

MIT License

---

## Author

PIRUTHIVIRAJ M  
Web3 & Frontend Developer
