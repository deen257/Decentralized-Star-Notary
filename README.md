# Notary Star Dapp on Goerli Testnet Network

In this project, a smart contract based on the ERC-721 standard is implemented, enabling the creation, exchange and transfer of stars from one account to another. The **_truffle_config.js_** file of this project is configured to deploy the smart contract in the Goerli Testnet. The **Infura** and **Metamask** are utilised in order to deploy the smart contract.

The **_Token name_** of the deployed token through the deployed smart contract is, **StarToken**.

The **_Token symbol_** of the deployed token through the deployed smart contract is, **STT**.

The **_Token address_** is **0xcf9D1987507d26E0BdA8ed4BBF8Caac993fCcF58**.

The **_Truffle_**, **_Solidity_** and **_Node_** versions of this project are the following:

```
Truffle v5.0.4 (core: 5.0.4)
Solidity v0.5.0 (solc-js)
Node v11.6.0
```

### Configuring your project

- Use NPM to initialize your project and install system specific software dependencies enclosed to package.json. Dependencies of this project are, truffle-hdwallet-provider, openzeppelin-solidity, etc.

```
npm install
```

## Usage

To test code follow the steps:

- install truffle `npm install -g truffle`(if not already installed).
- execute: `truffle compile` to compile the contracts
- execute: `truffle migrate --reset` to deploy the contracts to Granache

### Deploy the contract to Goerli Test Network

- set up an .env with your mnemonic seed and infura
- execute `truffle deploy --network goerli`

### Setup Front-end

- enter in app with 'cd app'
- execute `npm install` to install all node_modules required (if not already installed)
- execute `npm run dev` to start the front-end
