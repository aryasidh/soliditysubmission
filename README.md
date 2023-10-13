# soliditysubmission

# MyToken Solidity Smart Contract

 simple Solidity smart contract for a custom token named MyToken (META or MTA). This contract allows for the creation, minting, and burning of tokens.

## Table of Contents

- [Overview](#overview)
- [Contract Details](#contract-details)
- [Usage](#usage)
- [License](#license)

## Overview

This Solidity smart contract, named `MyToken`, is a basic example of a custom token on the Ethereum blockchain. It includes functionalities for minting (creating) and burning (destroying) tokens.

## Contract Details

The smart contract includes the following public variables and functions:

- `tokenName`: A string representing the name of the token, which is "META".
- `tokenAbbrv`: A string representing the token's abbreviation, which is "MTA".
- `totalSupply`: A public unsigned integer that tracks the total supply of tokens in circulation.
- `balances`: A mapping that associates Ethereum addresses with their token balances.

### Mint Function

The `mint` function allows the creation of new tokens and increases the total supply. It takes two parameters:

- `_address`: The Ethereum address to which the newly created tokens will be assigned.
- `_value`: The number of tokens to create.

### Burn Function

The `burn` function allows the destruction of tokens and decreases the total supply. It takes two parameters:

- `_address`: The Ethereum address that owns the tokens to be burned.
- `_value`: The number of tokens to burn.

## Usage

To use this smart contract, you can deploy it on an Ethereum testnet or the Ethereum mainnet using a development environment like Remix or Truffle. You can then interact with the contract using Ethereum addresses to mint and burn tokens.

Here's an example of how to use the `MyToken` contract:

1. Deploy the contract to an Ethereum network.
2. Mint tokens using the `mint` function, specifying the recipient address and the number of tokens to create.
3. Burn tokens using the `burn` function, specifying the owner's address and the number of tokens to burn.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



Happy coding!
