# MyToken Smart Contract

This project is a custom implementation of the ERC20 Token standard using the OpenZeppelin library. It features an ownable design pattern, allowing only the contract owner to mint tokens. Additionally, all users can burn their tokens. This contract also provides standard token transfer functionality.

## Dependencies

- OpenZeppelin Contracts: Open-source smart contracts library for secure development in Ethereum ecosystem.

- Hardhat: A development environment to compile, deploy, test, and debug your Ethereum software.

## Contract Details

### MyToken

This contract is the implementation of the token with the following functions:

- `mint`: Only accessible by the owner, this function allows the creation of new tokens.

- `burn`: Allows a user to destroy his own tokens.

- `transfer`: Allows a user to send tokens to another user.

- `transferFrom`: Allows a user to send tokens from one account to another.

## Scripts

The JavaScript code included in the project is meant to handle the deployment of the contract to the Ethereum network using Hardhat. 

`main()`: This function is responsible for deploying the contract and logging the address of the deployed contract.

## Installation

1. Clone the repository to your local machine.

2. Install the dependencies using npm:
```bash
npm install
```

3. Compile the smart contract using Hardhat:
```bash
npx hardhat compile
```

4. Deploy the contract to the local Hardhat Network:
```bash
npx hardhat run scripts/deploy.js
```

5. Interact with the contract using the Hardhat console:
```bash
npx hardhat console
```

Thank you
