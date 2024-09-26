# Trade Bridge

## Description
Trade Bridge is a decentralized commodity exchange platform that allows buyers and sellers to trade commodities in a trustless environment using blockchain technology. The platform incorporates tokenization, decentralized and NFT minting/burning to represent commodity ownership. It also handles disputes between parties and includes a fee system to sustain platform operations

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Running Tests](#running-tests)
4. [Deployment](#deployment)
5. [Features](#features)
6. [Future Features / Roadmap](#future-features-roadmap)
7. [Technologies](#technologies)
8. [Contributing](#contributing)
9. [License](#license)

## Installation
1. clone the repository
```
git clone https://github.com/dimka90/Block-Bridge.git
```

 ## Navigate to the project directory ##:
    ```bash
    cd Block-Bridge
    ```

 ## Install dependencies##:
    ```bash
     npm install
    ```

## Usage

### Compile Contracts:
```bash
npx hardhat compile
```
### Running Test
```bash
npx hardhat test
```

### Deploy the project
```bash
npx hardhat run /scripts/deploy.ts --network Lisk
```
### Present Features


### Seller
- Sellers can list new commodities available for trade by setting the value   for the commodity, the commodities are tokenized into a digital asset represented as an NFT to ensure traceability and ownership on the blockchain. sellers can also raise or respond to disputes. .

 
### Buyers 
- The buyer can buy commodity using LISKS Sepolia native token.
- On Successfull payment, an NFT will be issued to the Buyer to signify the own the commodity.

### System(Smart contract)
- Resolve Dispute 
When a dispute is raised, funds will be temporarily hold in the contract  until the the dispute is resolved and once the dispute is resolved the transaction can proceed and the commodity is transferred to the buyer or the seller account.

- The smart contract provide the plateform for the buyers and sellers to trade.
- The smart contract gives rating upon eacch successfull  to the seller.
## Future  Features

- Verifying users Identity using optimistic rollups.

## Technology used
The following technologies were used to build this project:

- **Solidity**: Smart contract language for Ethereum development.
- **Hardhat**: Ethereum development environment for compiling, testing, and deploying smart contracts.
- **JavaScript**: Used for writing deployment and test scripts.
- **Ethers.js**: JavaScript library for interacting with the Ethereum blockchain.
- **Node.js**: Runtime environment for running JavaScript code on the server.
- **Mocha/Chai**: Testing framework for writing unit tests for smart contracts.
- **Git**: Version control system to track changes and collaborate on the project.

