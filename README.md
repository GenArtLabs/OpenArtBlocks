# OpenArtBlocks

OpenArtBlocks is an open-source self-hosted approach to creating generative art on the Tezos and Ethereum blockchains.
This allows any artist to create generative art that is constructed only at the time of minting, thus making the art truly generative.

This repository is a hub for all the OpenArtBlocks-related projects:

### Tezos
* [Smart Contract](https://github.com/GenArtLabs/OpenArtBlocks-Smart-Contract-Tezos)
* [Backend](https://github.com/GenArtLabs/OpenArtBlocks-Backend-Tezos)
* [Frontend](https://github.com/GenArtLabs/OpenArtBlocks-Frontend-Tezos)

### Ethereum
* [Backend and Smart Contract](https://github.com/GenArtLabs/OpenArtBlocks-ethereum)

## FAQ

### Who is using OpenArtBlocks?
At the time of writing, [Blocks on Blocks](https://blocks-on-blocks.art) is the first and only NFT collection using OpenArtBlocks as its backbone.

### Why should I use OpenArtBlocks?
This toolkit provides a thoroughly tested, ready-to-use platform for artists who want to create truly generative artworks. The trick is to generate the artwork on demand by using a number generated at the time of minting (token hash). With OpenArtBlocks, you will create art that no one, not even yourself, can predict in advance.

Also, this being a self-hosted toolkit, you are not constrained by any rules or fear of censorship.

### Why did you open-source this project?
We want to give the community a project on which we can all build on. We want all artists and developers to join us on improving the generative NFT ecosystem.

Also, rather than simply trusting the contract creators, anyone can verify the code used to create the smart contract to make sure they can trust it. Also, you can create your own version to suit your needs.

Finally, we want artists - especially non-tech-savvy ones - to be able to express themselves through the means of truly generative art on the Tezos and Ethereum blockchains.

### How does it work?
OpenArtBlocks is split in three parts:
* The frontend interface designed for users to interact with your contract:
  * [Tezos](https://github.com/GenArtLabs/OpenArtBlocks-Frontend-Tezos)
* The backend server which serves metadata and token previews during the minting process:
  * [Tezos](https://github.com/GenArtLabs/OpenArtBlocks-Backend-Tezos)
  * [Ethereum](https://github.com/GenArtLabs/OpenArtBlocks-ethereum)
* The custom [FA2 (Tezos)](https://github.com/GenArtLabs/OpenArtBlocks-Smart-Contract-Tezos) or ERC721 (Ethereum) contract, backbone of your NFT collection.

During the time of minting, a server generates and serves the art to the users.
After the sale ends, you can then transfer all the assets (metadata, previews) on [IPFS](https://ipfs.io/) (or the like) for future-proof hosting.

We will soon provide you with ways to easily deploy an OpenArtBlocks instance on popular hosting platforms.

### What art generation tools are supported?
You can create animated artworks with the following technologies:
* [p5.js](https://p5js.org/)
* Native JavaScript

More are coming, please tell us what tools you want to see!

### Where do I start?
A tutorial is coming soon. For now you can join our [Discord server](https://discord.gg/xsun2M33Jt).

We will soon provide boilerplate code to start creating your artwork quickly.

### I have another question...
Ask away on our [Discord server](https://discord.gg/xsun2M33Jt), or open an issue on the relevant GitHub repository!
