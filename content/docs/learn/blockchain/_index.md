---
bookCollapseSection: true
weight: 1
description: "TLDR of what blockchain is"
---
# Blockchain
## What is a Blockchain?
The term "Blockchain" is derived from how digital blocks are cryptographically chained together. Stripping away other auxiliary features, the blockchain data structure consists fundamentally of 2 elements; the blocks and the chain. *A block can be thought of as a collated list of transactions* (you can think of them as tasks!).

< insert image of a block with some transactions >

In the diagram above, this block contains 6 transactions. Each transaction is initiated by someone with the purpose of achieving some desired outcome. For example, Alice (the initiator) wants to lend 5 bucks to Bob (desired outcome) i.e. the wallet balances of Alice and Bob should decrease and increase by 5 respectively once this transaction has completed. 

That said however, blocks by themselves are not very cool. A block is just a representation of tasks that have been aggregated together. But by leveraging on cryptography and some smart design choices, the "chain" that connects these blocks elevates this block data structure to a whole new level!

< insert image of blocks connected with a chain with genesis block header and latest block>

This upgrade enables *the automatic, immediate and instant propagation any changes (be it malicious, unintended or genuine) from an earlier block to the latest block*. Users are able to detect if an earlier block has been modified without having to comb through the entire chain! Talk about optimisation!

## In-depth look at how the "chain" works

The automatic, immediate and instant propogataion of any changes to earlier blocks in a blockchain is achieved through the cryptographic algorithm known as hashing. 

### Hashing

In short, hashing

A more 

To fully grasp how the "chain" enables the abovementioned functionality, we must first deconstruct blocks a little further. 


 we understand that the blockchain data structure consists of 2 elements; blocks



## 


How cool is that? It is cool right? No...? Okay maybe it is not entirely obvious now why this functionality is amazing so read the [benefits and usecases](benefits%20and%20usecases.md) page to understand better!