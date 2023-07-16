# mint_token

## Introduction

This repository contains the Solidity smart contract code for the  token.

## Contract Details

The Token.sol file contains the source code for the token contract. Here are the key details of the contract:

- Token Name: 21ct1090 Token
- Token Symbol: Symbol
- Total Supply: 0 (initially)

The contract includes standard ERC-20 functions such as balanceOf and transfer and includes functionalities for minting and burning tokens. 
The mint functionis only accessible only by the contract owner.

The contract owner has right to to mint new tokens. Other addresses can interact with the contract by transferring tokens and burning their own tokens.

## Deployment on Local Hardhat Test Network:-


1. Clone the repository.
2. Copy the code in remix ide.
3. Select the compiler version.
4. Select hardhat provider.
5. Deploy the contract.

6. You can now interact with the token contract through the provided functions.

   - Use the (balanceOf) function to check the token balance.
   - Use the (transfer) function to send tokens from your address to another address.
   - Use the (mint) function (accessible only to the contract owner) to mint

   - Use the (burn) function to burn a specific amount of your tokens.


## Authors

Dheeraj kaushik


