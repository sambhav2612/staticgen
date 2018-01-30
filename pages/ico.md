# Blockchaining Everything

## WTF is Blockchain

Blockchain is a network of distributed and decentralized systems to faciltate a procedure (of value) based on the needs of end-user on the underlying P2P network. In simple terms, it is a technology based on the concept of decentralizing some entity of value.

After Bitcoin was introduced in 2008-9, some anonymous person from Japan claimed to have built a solution to develop s/w on top of bitcoin in form of distributed digital ledgers. Digital Ledgers are nothing but a mechanism to process some entity of value (where the entity doesn't necessarily has to be in the financial domains) while other systems keep listening to it for changes.

### An example

Consider 4 people: `A, B, C and D` to be the primary nodes on the network of a private blockchain. Here's how things work from there on:

1. `Node A` has to send some money to `Node B`.
2. `Node A` initiates a transaction request on the network.
3. The request gets enqueued for verification of issuer's status on the network.
4. Upon verification, the transaction is written on the personal public ledger of the `Node A`, hence it is visible to every other node across the network.
5. The transaction may contain some cyptocurrency being used. (generally it does)
6. A block is generated for that transaction which might contain other transactions from this node as well as from other nodes.
7. This newly generated block is added to the chain of existing blocks, where each block can store as many as `n` number of transactions (not limited to/of having some economic value). New blocks are generated every `10 minutes or so`.
8. Hence the transaction is assumed completed and added to the chain of transactions of the network.