# Merkle Trees

Merkle Trees are a fundamental concept in blockchain technology.

## What is a Merkle Tree?

A merkle tree is a type of hash tree in which each leaf node is labeled with the cryptographic hash of a data block, and each non-leaf node is labeled with the cryptographic hash of its child nodes' labels. The majority of hash tree implementations are binary (each node has two child nodes), but they can also have many more child nodes.

A typical Merkle Tree looks something like this:
![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Hash_Tree.svg/1920px-Hash_Tree.svg.png)

## Simple Example

Let's say we have 4 transactions: "Transaction A", B, C and D. All of them are executed in the same block. Each of these transactions is going to get hashed. Let's call those hashes "Hash A", B, C, and D respectively.

The following would be the resulting Merkle Tree of these transactions:
![](https://i.imgur.com/wj5TKJ8.jpg)