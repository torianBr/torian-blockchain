# Decentralized-Torian-Project

Motivation

All the current implementations of blockchains are tightly coupled with the larger context and problems they (e.g. Bitcoin or Ethereum) are trying to solve. This makes understanding blockchains a necessarily harder task, than it must be. Especially source-code-wisely. This project is an attempt to provide as concise and simple implementation of a blockchain as possible.


What is blockchain?

From Wikipedia : Blockchain is a distributed database that maintains a continuously-growing list of records called blocks secured from tampering and revision.


Key concepts of Torian

-HTTP interface to control the node
-Use Websockets to communicate with other nodes (P2P)
-Super simple "protocols" in P2P communication
-Data is not persisted in nodes
-No proof-of-work or proof-of-stake: a block can be added to the blockchain without competition
