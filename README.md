# MetamaskConnect - Next.js, Moralis:

This is a minimalistic project to show us how we can connect to Metamask using Moralis in Next.js / React.

This could just as easily be done in TypeScript.

This project starts with Next.js boilerplate, by running `yarn create next-app nextjs-web3modal-metamask-connect`

# Getting Started

## Requirements

- [Metamask](https://metamask.io/)
  - This is a browser extension that lets you interact with the blockchain.

## Quickstart

1. Clone the repo and install dependencies

2. Now, in my repositories, you need to clone hardhat-simple-storage in a new window
   - Then, you'll need to open up a second terminal and run:
```
yarn hardhat node
```

This will deploy a sample contract and start a local hardhat blockchain.

3. Connect your [Metamask](https://metamask.io/) to your local hardhat blockchain.

> **PLEASE USE A METAMASK ACCOUNT THAT ISNT ASSOCIATED WITH ANY REAL MONEY.**
> 
> I usually use a few different browser profiles to separate my metamasks easily.

In the output of the above command, take one of the private key accounts and [import it into your metamask.](https://metamask.zendesk.com/hc/en-us/articles/360015489331-How-to-import-an-Account)

Additionally, add your localhost (with chainId 31337) to your Metamask.

But add your own Kovan PC URL (via Alchemy) of course.

4. Open the UI

Then, back in your first terminal, run:

```
yarn dev
```

And open the browser to the localhost URL it gives you.

5. Hit buttons

You'll be brought to the UI after running `yarn dev` which has exactly 2 buttons. Hit `connect` (and accept in your Metamask) then hit `execute` and you'll send a transaction to your local hardhat.

### Important localhost note

If you use metamask with a local network, everytime you shut down your node, you'll need to reset your account. Settings -> Advanced -> Reset account. Don't do this with a metamask you have real funds in.

# Full Examples

- [Ethereum Boilerplate](https://github.com/ethereum-boilerplate/ethereum-boilerplate)

# Thank you!
