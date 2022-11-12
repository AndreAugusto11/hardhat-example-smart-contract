# Example of a solidity smart contract written using Hardhat

To compile the smart contract:

`npm hardhat compile`

To run the tests:

`npm hardhat test`

Deploying in the embedded local network:

`npx hardhat run scripts/deploy.js`

Deploying in Goerli Test Network, after adding network in `hardhat.config`:

`npx hardhat run scripts/deploy.js --network goerli`