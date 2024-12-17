# DE-VOTING-SYSTEM


## Description
This is a decentralized voting application built with React, TypeScript, and Ethereum smart contracts.

## Features
- Vote for candidates on the blockchain.
- See real-time voting results.
- Switch between mock mode and blockchain mode.

## Requirements
- MetaMask or another Ethereum wallet.
- Node.js installed.

## Install dependencies:

Navigate to the project directory and install the required dependencies:

cd YOUR_REPOSITORY_NAME
npm install

Install Dependencies

## Run the following command to install the required dependencies:

npm install


## Smart Contract Deployment

The app interacts with an Ethereum smart contract. To deploy the contract, you can use either Truffle or Hardhat.

For Truffle: Truffle Deployment Guide
For Hardhat: Hardhat Deployment Guide
Once the contract is deployed, update the contract address in App.tsx:


const contractAddress = 'YOUR_CONTRACT_ADDRESS';

##Start the Application

Run the following command to start the development server:


npm start
This will start the app, and you can access it in your browser at http://localhost:3000


