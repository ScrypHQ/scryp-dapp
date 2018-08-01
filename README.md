# Scryp App

This repository holds the primary codebase for Scryp dApp development (currently on the Ethereum platform.)

# Overview:

*Define repo structure here

# Dev environment:

Visual Studio, Cloud9

# Test environment:

Smart contracts have been tested on ethereumjs-testrpc using
Truffle Ganache CLI. Ropsten test network is the next phase. This test network
is the most logical choice for a few reasons. First, it uses proof of work
(the same as the main Ethereum network) while others like RinkeBy, Sokol, and Kovan
use proof of authority. It makes the most sense to test our contracts
in an environment that is more similar to the actual network. Furthermore, Ropsten
has the largest chaindata size of the test networks and is the only one to support
both geth and parity--the two most popular clients. Although Ropsten isn't immune to
spam attacks, and is thus less stable than the other test networks, for our usage this
shouldn't be too big of an issue since our contract has central minting capabilities, which
would enable us to recreate the accounts from a previous block snapshot.
    
For fast, formal Solidity analysis, https://remix.ethereum.org/ is
a helpful environment.
    
# Auditing tools:

Oyente is an analysis and visualization suite for Solidity contracts:
https://github.com/melonproject/oyente

http://securify.ch/ is another option for formal verification of contracts.
    
# Some best practices:

The Monax (formerly Eris Industries) Solidity tutorial
for systems of smart contracts:
https://monax.io/docs/solidity/solidity_1_the_five_types_model/
    
A useful and comprehensive organizational model for GitHub.
http://nvie.com/posts/a-successful-git-branching-model/
    

# For more information:

Gopi Kotaru | Chief Technical Officer | Blockchain Adviser | gopi@scryp.io

Tyler Tracy | Co-Founder | Blockchain Architect | tyler@scryp.io
