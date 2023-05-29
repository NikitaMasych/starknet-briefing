# Starknet Briefing

Current Starknet (May 2023) represents volatile and growing set of technologies, 
there plenty of information is outdated and a little covers in-depth. 
Therefore, this guide is intended to help you begin assimilation with it, 
without wasting time searching for useful resources.

### Contents

- [Summary](#summary)
- [Development](#development)
    - [Setup](#setup)
    - [IDE](#ide)
    - [Wallet](#wallet)
    - [Learn Cairo 1](#learn-cairo-1)
    - [Starknet Explorers](#starknet-explorers)
- [Research](#research)

## Summary

Starknet is a layer 2 zk-rollup over ethereum.
I recommend read [this](https://david-barreto.com/starknets-architecture-review/)
article to quickly understand what is going on.

## Development

In Starknet, smart contracts are written in Cairo.
Important to differentiate two types of it:

* Cairo 0:  [cairo-lang](https://github.com/starkware-libs/cairo-lang)
* Cairo 1: [cairo](https://github.com/starkware-libs/cairo)

Former one is a bit more mature, with greater amount of docs/infrastructure and projects in it, 
yet with peculiar syntax and becoming deprecated, whereas second is heavily improved, rewritten in Rust version.

You need to know about existence of the first one, but focus and use primarily Cairo 1.

### Setup:

* [Setup environment](https://docs.starknet.io/documentation/getting_started/environment_setup/)
* [Setup account](https://docs.starknet.io/documentation/getting_started/account_setup/)

### IDE:

To have the basic syntax highlighting, 
use VS Code + [Cairo 1 extension](https://github.com/starkware-libs/cairo/tree/main/vscode-cairo)

**NOTE**: you need to install it yourself, because cairo extension from VS Code marketplace is intended for Cairo 0.
 
### Wallet:

Two similar to EVMs' Metamask wallets are available for usage in Starknet:

* [Argent X](https://www.argent.xyz/argent-x/)
* [Braavos](https://braavos.app/)

If you don't want to sort out differences between them, just choose first, and you won't miss.

### Learn Cairo 1:

* [starknet-cairo-101](https://github.com/starknet-edu/starknet-cairo-101)

### Starknet Explorers:

* [starkscan](https://starkscan.co/)
* [voyager](https://voyager.online/)

## Research

Beneath are thorough knowledge-bases to enhance your overall understanding:

* [Awesome ZKP](https://github.com/matter-labs/awesome-zero-knowledge-proofs)
* [Awesome Starknet](https://github.com/gakonst/awesome-starknet)
