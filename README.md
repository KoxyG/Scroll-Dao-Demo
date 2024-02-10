# English Auction NFT Smart Contract

## Description

This project implements a Decentralized Autonomous Organization (DAO) smart contract where members can propose, vote on, and execute proposals autonomously. The contract allows for the management of members, creation of proposals, voting on proposals, and execution of approved proposals.

## Features

- Membership management
- Proposal creation and voting
- Proposal execution based on member votes

## Usage

### 1. Deploying the DAO Smart Contract

Before starting to use the DAO, deploy the DAO smart contract to an Ethereum-compatible blockchain using your preferred deployment method.

### 2. Adding Members to the DAO

Once the DAO contract is deployed, the owner of the contract can add members to the DAO using the `addMember` function. Members are essential for creating and voting on proposals.

```solidity
// Add a member to the DAO
function addMember(address _member) public {...}
