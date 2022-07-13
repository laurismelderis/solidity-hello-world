# Hello world solidity contract

The purpose of this project is to learn the ways of contracts in blockchain.

## To test the project you should:

### Setup environment:

1. Setup alchemy profile (You will need `API_URL` and `API_KEY` for .env file)
2. Setup MetaMask wallet (In wallet you should use RinkebyETH for test purposes + you can get free fake eth there in order to test the project)
3. After setting up the MetaMask wallet, from the Rinkeby Test Network account export the private key (Necessary for `PRIVATE_KEY` in .env)
4. Get node.js

### Finish project setup:

1. In the project do `npm i`
2. Do `npm deploy` for deploying the contract with initial message
3. After deployment save the contract key in .env [in .env file -> `CONTRACT`]
4. Then do `npm interact` to update the deployed contract with new message