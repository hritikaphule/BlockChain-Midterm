# CryptoZombies DApp - Midterm Project

## Team Members

- **Hritika Phule** - 828429332 - hritika@csu.fullerton.edu
- **Sarita Joshi** - 884441866 - saritajoshi@csu.fullerton.edu
- **Hitesh Mali** - 885166850 - hiteshmali@csu.ullerton.edu
## Project Overview

CryptoZombies is an interactive coding tutorial that teaches users how to build Ethereum smart contracts with Solidity. For our midterm project, we developed a decentralized application (DApp) that allows users to create and level up their zombie army and kitty.

## Enhancements Implemented

1. **Deployment on Sepolia Testnet:** We deployed our smart contracts on the Ganache testnet to demonstrate real-world blockchain interaction.
2. **Improved Website Design:** We revamped the user interface for a more engaging and intuitive experience.
3. **Creating Kitties Contract on the Backend:** We created a custom kitty smart contract to create new kitties on ganache locally.
4. **Automated retrieving the zombieOwnership contract address immediately upon its deployment on Ganache, eliminating the need for a hardcoded address in the frontend.**
5. **Migrated front-end code to use ReactJS**
6. **Allow users to create their zombies with custom names**
7. **Zombies cards are dynamically changed based on current user account**
8. **Each User can create up to 6 zombies**
9. **Used Latest Metamask Web3 API to connect to Ganache**
10. **Custom Script to fetch new and updated ABI from the build folder to be used in front-end**

## Installation and Setup

To set up and run the CryptoZombies DApp on your local machine, follow these steps:

1. Clone the repository:
   git clone https://github.com/hritikaphule/BlockChain-Midterm.git

2. Install dependencies:
   npm install

3. Install ganache and add this project to workspace using truffle-config.js file in the root directory

4. Connect your MetaMask wallet to the local network and import accounts from Ganache.

5. Deploy the smart contracts on Ganache:
   truffle compile, truffle migrate

6. Run the frontend application:
   npm run dev

## Deployment of Testnet

To deploy and test GanacheTestnet, follow these steps:

1. Setup repo on Remix by importing it from Github:
   https://remix.ethereum.org/

## Technologies Used

- Solidity for smart contracts
- Truffle for smart contract deployment and testing
- Ganache for a local blockchain network
- Sepolia for a private Ethereum network
- Web3.js for blockchain interaction
- React for frontend development
