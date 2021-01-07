# Duckchain

## Description

Duckchain is a personal blockchain algorithm that I have created. Compared to how a blockchain usually works, it's not altered too much. If I do make any changes to the base algorithm, I will let you know.

## Transactions

The main part of the blocks in the blockchain are the transactions. The transaction will contain the address of a sender, the address/addresses of the receivers, and data targeted to each of the receivers. This data could be anything, from transactional data to a personal message.

## Addresses

Like with Bitcoin, all the senders and receivers will have addresses with public and private keys attached to them. I'm not sure whether or not I should tie the key generation to the address itself, since there's an obvious security flaw in doing so.

## Todo:

- Flesh the readme out with better information
- Create programs to create, display, sign, and verify transactions
- Create the block data structure
- Create the program that nodes will use