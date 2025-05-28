# Crowdfunding using Crypto
A crowdfunding platform that allows crypto funds.

![Home Page](./home-page.png)

## Technology Used
### Frontend
1. React
2. TailwindCSS
3. React Router
4. ThridWeb SDK

### Backend
1. ThirdWeb Platform
2. Solidity

### Features
1. View all crowdfunding campaigns.
2. Create a new campaign with required details.
3. Connect your Metamask wallet to make donations.
4. Built-in currency-to-Ethereum converter.
5. Dark and Light mode toggle.

## Getting Started
Follow these steps to run the project locally:

### Prerequisites
 * Node.js v16 or higher
 * Metamask Wallet
 * ThirdWeb account (free)

### Project Structure
```
root/
├── client/         # React frontend
└── web3/ # Hardhat backend (Solidity)
```
### Frontend (Client)
1. Navigate to the client directory:
```
cd client
```
2. Install dependencies:
```
npm install
```
3. Create a .env file in the following format and paste the content you get from the thrid web platform
```
VITE_CLIENT_ID=
VITE_CONTRACT_ADD=
```
4. Run the development server:
```
npm run dev
```
5. Build for production:
```
npm run build
```
6. Deploy to ThirdWeb storage:
```
npm run deploy
```

### Smart Contract (Backend)
You'll need to connect your metamask wallet when deploying with ThirdWeb.
1. Navigate to the smart_contract directory:
```
cd smart_contract
```
2. Install dependencies:
```
npm install
```
3. Create a .env file in the following format and paste the content you get from the thrid web platform
```
PRIVATE_KEY==
```
4. Build the contracts:
```
npm run build
```
5. Deploy your contract:
```
npm run deploy
```
## Reference
You can follow this [YouTube Tutorial](https://youtu.be/BDCT6TYLYdI?si=lA_SF7ZlGCck2tM2) for setup and deploying.



