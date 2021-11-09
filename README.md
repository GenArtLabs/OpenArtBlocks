# OpenArtBlocks

OpenArtBlocks is an open-source self-hosted approach to distributing generative art on the Tezos and Ethereum blockchains.
This allows any artist to create generative art that is constructed only at the time of minting, thus making the art truly generative.

This repository is a hub for all the OpenArtBlocks-related projects:

### Tezos
* [Smart Contract (Tezos)](https://github.com/GenArtLabs/OpenArtBlocks-Smart-Contract-Tezos)
* [Backend (Tezos)](https://github.com/GenArtLabs/OpenArtBlocks-Backend-Tezos)
* [Frontend (Tezos)](https://github.com/GenArtLabs/OpenArtBlocks-Frontend-Tezos)

### Ethereum
* [Backend (Ethereum)](https://github.com/GenArtLabs/OpenArtBlocks-ethereum)
* The smart contract and frontend repositories are coming soon

## FAQ

### Who is using OpenArtBlocks?
At the time of writing, [Blocks on Blocks](https://blocks-on-blocks.art) is the first and only NFT collection using OpenArtBlocks as its backbone.

### Why should I use OpenArtBlocks?
The goal of this project is to bring more trust into the code used to run the NFT collection rather than for users to simply trust the collection administrator to keep their promises.

Also, this being a self-hosted toolkit, the art creator is not constrained by an authority for their creations to follow their rules. The creator has their own rules.

### How can I create my own collection with OpenArtBlocks?
OpenArtBlocks is split in three parts:
* The frontend interface ([Tezos](https://github.com/GenArtLabs/OpenArtBlocks-Frontend-Tezos)) designed for users to interact with your contract;
* The backend server ([Tezos](https://github.com/GenArtLabs/OpenArtBlocks-Backend-Tezos), [Ethereum](https://github.com/GenArtLabs/OpenArtBlocks-ethereum)) which serves metadata and token preview generation during the minting process;
* The custom [FA2 (Tezos)](https://github.com/GenArtLabs/OpenArtBlocks-Smart-Contract-Tezos) and ERC721 (Ethereum) contracts which allow you to manage your NFTs.

### Does that mean I have to host it myself?
During the time of minting, yes. You can then transfer all the assets (metadata, previews) on IPFS for future-proof hosting.

We will soon provide you with ways to easily deploy an OpenArtBlocks instance on popular hosting platforms.

### How can I create art for this medium?
You can create animated artworks using JavaScript with the following technologies:
* Canvas + [p5.js](https://p5js.org/)
* SVG

We will soon provide boilerplate code to start creating your artwork quickly.
