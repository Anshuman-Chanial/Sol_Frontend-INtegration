# Metacrafters ATM Project

A simple decentralized ATM system using Ethereum smart contracts and a React frontend.

## Description

The Metacrafters ATM Project is a decentralized application that allows users to interact with an Ethereum-based ATM. Users can deposit and withdraw ETH, check their balance, gas left, and the timestamp of the current block. The project consists of three main components: a Solidity smart contract (Assessment.sol), a React frontend (index.js), and a deployment script (deploy.js).

## Getting Started

### Installing

1. Clone the repository to your local machine:
    sh
    git clone https://github.com/your-repo/metacrafters-atm.git
    cd metacrafters-atm
    
2. Install the necessary dependencies:
    sh
    npm install
    

### Executing program

#### Deploying the Smart Contract

1. Compile and deploy the smart contract using Hardhat:
    sh
    npx hardhat run scripts/deploy.js --network <your-network>
    
    Replace <your-network> with the network you are deploying to (e.g., localhost, rinkeby, etc.).

2. Note the deployed contract address output by the deployment script.

#### Running the Frontend

1. Update the contract address in index.js:
    javascript
    const contractAddress = "YOUR_DEPLOYED_CONTRACT_ADDRESS";
    
    Replace YOUR_DEPLOYED_CONTRACT_ADDRESS with the address from the deployment step.

2. Start the React development server:
    sh
    npm run dev
    

3. Open your browser and navigate to http://localhost:3000.

## Help

If you encounter any issues or need further assistance, consider the following:

- Ensure you have MetaMask installed and configured.
- Check your network configuration in Hardhat and MetaMask.
- Verify your contract address is correctly set in the frontend code.

## Authors

Anshuman

## License

This project is licensed under the MIT License
