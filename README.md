
# MyToken (MTK)

## Overview
MyToken is a simple ERC-20 compatible token built on Ethereum for learning purposes.

## Token Details
- **Name**: MyToken
- **Symbol**: MTK
- **Decimals**: 18
- **Total Supply**: 1,000,000 MTK

## Features
- ✅ Standard ERC-20 implementation
- ✅ Transfer tokens between addresses
- ✅ Approve and transferFrom functionality
- ✅ Event emission for transparency
- ✅ Balance tracking

## How to Deploy
1. Open [Remix IDE](https://remix.ethereum.org/)
2. Create a new file `MyToken.sol`
3. Paste your Solidity contract code
4. Compile using Solidity `0.8.x`
5. Deploy with the desired total supply

## How to Use

### Check Balance
```solidity
balanceOf(address) → returns uint256 

 Transfer Tokens
transfer(address to, uint256 amount) → returns bool

 Approve Spending
approve(address spender, uint256 amount) → returns bool

Transfer on Behalf
transferFrom(address from, address to, uint256 amount) → returns bool