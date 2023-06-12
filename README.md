# Quests Base Goerli

This project demonstrates a basic NFT sol. It comes with a sample NFT contract, a test for that contract, and a script that deploys that contract.

Create .env for YOUR_PRIVATE_KEY
```
WALLET_KEY=<YOUR_PRIVATE_KEY>
```

Try running quest of the following tasks:

```shell
npx hardhat compile
npx hardhat run scripts/deploy.ts --network base-goerli
npx hardhat verify --network base-goerli <deployed address>

```
