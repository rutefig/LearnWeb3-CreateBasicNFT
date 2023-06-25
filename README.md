# Learn Web3 - Build a basic NFT contract

This project was done while doing the LearnWeb3 Ethereum Developer Degree. The goal was to simply write a super basic NFT smart contract and deploying it to Sepolia Test Network.

This Project contains a smart contract file `NFTee.sol` and a simple script to deploy it. It uses hardhat for the deployment process.

If you want to try it just run the following commands to install the dependencies, compile the smart contract and run the script to deploy it.

```shell
npm install
npx hardhat compile
npx npx hardhat run scripts/deploy.js --network sepolia
```