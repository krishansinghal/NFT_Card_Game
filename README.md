# Blockchain NFT Game

This project is a blockchain NFT game. The user can create a roleplay NFT card to play a game. After creating an account, user can create a new battle ground or can join the existing battle ground.\\
The project is build using the Solidity for the smart contract, javascript and ReactJS. 

## Setup

1) Open the terminal and Copy the repository in local system using the following command:
```bash
git clone https://github.com/krishansinghal/NFT_Card_Game
```
2) Go to the web3 Folder:
```bash
cd web3
```
3) open the terminal and Install the dependencies:
```bash
npm i
```
4) Configure the `.env` file:
- Create a `.env` file in the root of `web3` folder and paste the require environmental variable:
```bash
PRIVATE_KEY=YOUR-PRIVATE-KEY
```
5) Open a new terminal and go to the client folder:
```bash 
cd client
```
6) Install the dependencies:
```bash
npm i
```

## Wallet Setup
This Project is work with the `core` wallet of `Avalanche`. If you do not have the it then download the `core` wallet in  your system.
- Open the `chrome` browser and go to `extension` tab and search `core` wallet. Add this extension  to browser.
- Create an `account` in the wallet. Use the below link video  to understand the `core` wallet.
```bash 
https://youtu.be/hQL4H0Qb6ZE?feature=shared
```
`Note: make sure to connect the wallet with network using secure pass phrase.`

- Add some `fuji faucet(c-chain)`  in your wallet.

## Compilation & Deployment
Open the terminal and Go to the `web3` folder;
```bash 
cd web3
```
``Note: Make sure to paste your wallet `private key` in the `.env` file.``

- Open the Terminal and run the following commands:
```bash 
npx hardhat compile
```
-Run the following command to deploy the contract:
```bash
npx hardhat run ./scripts/deploy.js
```
Copy the deployed `Contract Address` and  paste it into the `client/src/contract/index.js` file.

## Run the Application
Open the new terminal and go to `client` folder:
```bash
cd client
```
Run the following command to start the application:
```bash
npm run dev
```
It will start the server at  `http://localhost:5173/`