# Functions-Errors
# SuperToken Smart Contract

This smart contract is designed to implement a custom ERC20 token named "SuperToken". It includes basic functionalities such as `minting`, `burning`, and `transferring` tokens, with additional ownership checks to ensure that only the contract owner can perform certain actions.

## Features

### Public State Variables:
- **`owner`**: The address of the contract owner, set during contract deployment.

### Functions:
- **`constructor`**: Initializes the token with the name "Superman" and symbol "SPT", sets the deployer as the owner, and mints an initial supply of 500,000 tokens to the owner's address.
- **`mint`**: Allows the owner to create new tokens and assign them to a specified address.
- **`burn`**: Allows any token holder to destroy a specified amount of their tokens.
- **`transfer`**: Overrides the default ERC20 `transfer` function to include an additional check to ensure that tokens are not transferred to the zero address.

## Usage

### Deploying the Contract
1. Open the Remix IDE or any other Solidity-compatible IDE.
2. Copy and paste the contract code into a new Solidity file.
3. Compile the contract using the Solidity compiler version 0.8.0 or higher.
4. Deploy the contract to an Ethereum network.

## Authors
- Rajkiran
- Email: rajkiransanjerwas@gmail.com
- University ID: 22BCS15465
- Video Link: https://www.loom.com/share/12b8c65dcd1b4239a8eb9b8a4bbdd762 
