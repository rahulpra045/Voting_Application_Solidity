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

## Resources
* Solidity Documentation: https://docs.soliditylang.org/
* Hardhat Documentation: https://hardhat.org/hardhat-runner/docs/getting-started
* OpenZeppelin Contracts Documentation: https://docs.openzeppelin.com/contracts/3.x/
* Ethereum Voting App Tutorial: https://dapp.vote/
* Guide to Developing an Ethereum Decentralized Voting Application: https://www.freecodecamp.org/news/developing-an-ethereum-decentralized-voting-application-a99de24992d9/

## Screenshots


## Installation
![Screenshot (25)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/89b448ce-7441-43e1-befe-fc7d2b4405cf)
![Screenshot (28)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/08199442-ee90-43c4-b922-f026cf998fbb)
![Screenshot (38)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/4208f392-caeb-4493-b9d8-8520d9cfd7ec)
![Screenshot (55)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/bb360d45-491d-4d32-8a38-c14e0f8cc401)
![Screenshot (56)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/176fe491-c820-47d9-b61a-98cce7eaada3)
![Screenshot (57)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/2d2c6fba-0aae-4cbf-9f0a-00f58e719ee4)
![Screenshot (59)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/b1f0cab0-7e0b-4e98-9baa-ef8825fc3554)
![Screenshot (60)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/887fdcac-9480-43b3-a012-34d334422328)
![Screenshot (61)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/c9720fd9-d7ce-49c7-a6f4-c90a60308cc7)
![Screenshot (62)](https://github.com/rahulpra045/Voting_Application_Solidity/assets/98214910/fbe1a298-21d5-4f55-8414-a412bdd45d7c)


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
