## Voting_Application_Solidity

This repository contains a simple voting application built with Solidity, a programming language for smart contracts on the Ethereum blockchain.

## About the application
This application allows users to:

* Create a ballot: A user can create a ballot with a title, description, and list of options or candidates.
* Set voting period: The user can specify a start and end date and time for the voting period.
* Vote: Any user can cast their vote for one option or candidate in a ballot.
* View results: Once the voting period is over, anyone can view the total votes for each option and the winner(s) based on the election rules.

## Features
* Transparency: All votes are stored on the Ethereum blockchain, ensuring transparency and immutability.
* Security: Votes are encrypted and cannot be tampered with.
* Accessibility: Anyone with an Ethereum wallet can participate in the voting process.
* Auditability: The voting process is auditable by anyone, increasing trust and accountability.

## Technologies 
* Solidity: Programming language for smart contracts on the Ethereum blockchain.
* Hardhat: Development environment for building, testing, and deploying smart contracts.
* OpenZeppelin Contracts: Library of secure and tested smart contract components.

## Getting started

## Prerequisites:

You must have Node.js and NPM installed on your system.
You should have some understanding of Solidity and smart contracts.

## Installation:

* Clone this repository to your local machine.
* Open a terminal window and navigate to the project directory.
* Install the required dependencies by running npm install.
* Compile the smart contracts by running npx hardhat compile.
* Deploy the smart contracts to a testnet by running npx hardhat run scripts/deploy.js.

## Testing:

* You can test the smart contracts using Mocha and Chai.
* Run the tests by running npx hardhat test.

## Usage:

You can interact with the smart contracts using a web3 library like Web3.js or Metamask.
Refer to the contract documentation for more information on how to interact with the specific functions.

## Documentation:

The contract documentation is available in the docs directory.
The documentation includes detailed information about the contracts, functions, and variables.
Contributing:

## License:
This project is licensed under the MIT license.
See the LICENSE file for more information.

## Resources
* Solidity Documentation: https://docs.soliditylang.org/
* Hardhat Documentation: https://hardhat.org/hardhat-runner/docs/getting-started
* OpenZeppelin Contracts Documentation: https://docs.openzeppelin.com/contracts/3.x/
* Ethereum Voting App Tutorial: https://dapp.vote/
* Guide to Developing an Ethereum Decentralized Voting Application: https://www.freecodecamp.org/news/developing-an-ethereum-decentralized-voting-application-a99de24992d9/

## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.

```shell
npx hardhat compile
npx hardhat run --network sepolia scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. You can also use another blockchain by writing the blockchain's endpoint in hardhat-config.

Once you have pasted your private key and contract address in the .env file, simply run command

```shell
npm start
```
