


Hi! Here some our recommendations to get the best out of BLACKBOX:

Be as clear as possible

There is no need commas (,) and any punctuation

Try ending the question in what language you want the answer to be, e.g: ‘connect to mongodb in node js’
or you can just
Watch tutorial video
Here are some suggestion (choose one):
Write a function that reads data from a json file
How to delete docs from mongodb in phyton
Connect to mongodb in nodejs
Ask any coding question
send
refresh
Blackbox AI Chat is in beta and Blackbox is not liable for the content generated. By using Blackbox, you acknowledge that you agree to agree to Blackbox's Terms and Privacy Policy
# Decentralized Voting Application

This is a demo application to implement voting in solidity smart contract using ReactJS. 

[Youtube Tutorial](https://youtu.be/eCn6mHTpuM0)

## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.

```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. You can also use another blockchain by writing the blockchain's endpoint in hardhat-config.

Once you have pasted your private key and contract address in the .env file, simply run command

```shell
npm start
```
