# Roar: Web3 + Smart Contract

This project uses Web3 to interface with a Solidity smart contract. It uses hardhat for development and deploys to the rinkeby testnet. The project was developed based on the @buildspace Web3 App with Solidity + Ethereum Smart Contracts project. The smart contract + web3 front-end allows a user to easily send a message (a 'roar'). The front-end react app retrieves these messages from the Ethereum blockchain using Alchemy and displays them.


To compile, run, and deploy the smart contract to rinkeby:

```shell
npx hardhat compile
npx hardhat run scripts/run.js
npx hardhat run scripts/deploy.js --network rinkeby
```

Try it live!
https://waveportal-starter-project.adagiox.repl.co
