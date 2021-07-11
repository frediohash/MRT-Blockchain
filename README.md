# MRT-Blockchain

Create genesis block that will be called over blockhain.

## Node.js (Install)

Requirements:

- npm install -g npm


## Usage

- cd MRT-Blockchain
- node main.js

## Description

- In block change data to transactions
- Remove index of block and genesis block
- Create class Transaction(fromAddress, toAddress, amount)
- Add property named pendingTransactions that empty array in class Blockchain
- Add property miningReward = 100 in class Blockchain
- Create method minePendingTransaction(miningRewardAddress) in class Blockchain
- Create method createTransaction(transaction) and push it to pendingTransaction
- Create method getBalanceOfAddress(address) and add two for
- Show the result with fredio.createTransaction(new Transaction())

## Best Ways
- We need add miningRewards
- We need the place to store the transactions
- We need new method to mining the pending transactions
- After block been mined, we create new transaction to give miningReward
- The miningReward will be sent after next block is mined




