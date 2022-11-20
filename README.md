# Decentralized Banking System (DeFi Bank)
This repository focuses on development of a decentralized banking system which is a DApp built on Ethereum blockchain with smart contract on solidity.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/202927689-6c3fe287-09aa-44d3-ae40-82f1e53f7765.png">
</p>

DeFi Bank provides Witdraw, borrow and payoff fucntionalities. All the data and business logic are stored and run on Ethereum blockchain by smart contracts.

## Theory
2019 was the year of Decentralized Finance, aka DeFi. Simply put DeFi is the collective name given to an ecosystem of financial applications built on top of the blockchain  also known as Decentralized Banking. The main aim of DeFi is to create a financial service ecosystem that’s open-source, permissionless, transparent and without any central authority. Within this ecosystem, the users have full control over their assets and they can interact with the ecosystem through decentralized applications (dApps).

Smart contracts are at the heart and soul of DeFi. A contract is a legally binding document between two parties, which is overseen by a third-party, usually a lawyer. A smart contract works similarly, except for two game-changing modifications – it is self-executing and doesn’t need a third-party for overseeing. [[1](https://blockgeeks.com/guides/decentralized-banking/)]

Decentralized Banking Use Cases

Some of the popular DeFi use cases, namely:
- Borrowing and Lending.
- Monetary banking services.
- Decentralized marketplaces.
And, in this study, DeFi Bank provides borrowing and lending which are implemented on solidity with smart contracts.

## DeFi Bank Capabilities
Here are three main functionalities of DeFi Bank provides. Witdraw, borrow and payoff are provided for now but the functionalities will be improved day by day.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/202927223-abe54161-75a8-4b26-b80d-9a8d37c188d6.jpg">
</p>

## Installation

### Setup

- **Node.js**

      sudo curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
      nvm install 12.18.3
      node -v

- **Truffle**

      sudo npm install -g truffle@5.1.39 --unsafe-perm=true

- **Ganache** installation guide can be found in [here](https://www.trufflesuite.com/ganache).

- **MetaMask** installation guide can be found in [here](https://metamask.io/).

### Commands

- Install necessarily Node.js packages

      npm install

- Deploy smart contracts to the Ethereum blockchain

      truffle migrate --reset
      
- Deploy and run the front-end application

      npm start run
      
- Run the scripts to issue tokens

      truffle exec scripts/issue-tokens.js

Demo of the DApp with the screenshots can be found on [this wiki page](https://github.com/ahmetozlu/defi_yield_farming/wiki/Demo-of-the-DApp).

## Citation
If you use this code for your publications, please cite it as:

    @ONLINE{
        author = "Ahmet Özlü",
        title  = "DeFi Banking System",
        year   = "20212,
        url    = "https://github.com/ahmetozlu/decentralized_banking_system"
    }

## References
This project was built on top of **Dapp University** implementation, [here](https://github.com/dappuniversity/dbank) you can find more details.

## Author
Ahmet Özlü

## License
This system is available under the MIT license. See the LICENSE file for more info.
