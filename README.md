We'll point you to the docs and repos you need to get started: first, this README contains a "How to Get Started" section and further below, we have included a brief introduction to IOV for those not already familiar with the project. 

# How to Get Started

would it make sense to start the document with something like this (i am not tech enough to write it correctly but hopefully you get the idea):

- we are building technology to run a blockchain of names, the BNS, and build clients for our blockchain. The code to do this is in iov-one/weave. You can run a validator of the blockchain by running _this_code_ and you can build a client to the blockchain by using _this_code_

- we are also building a technology that allows you to build apps that can access all blockchains. We are still at the beginning, but you can start building an app that works with <tendermint and lisk> at the moment, soon ethereum, by using our library iov-core, follow _here_ to get started. <we can talk of atomic swap here if it works?>

- we have build the first app with iov-core, the IOV Wallet, and you can see how iov-core is used and add functionalities in this project _iov-one/iov-wallet_.

<and if the BCP specs are ready to share, we can also be explicit about where the code is and how people can use it to enhance iov-core>

does it make sense?

You're free to explore the GitHub but presently, the best steps to start with are:

1. If you're interested in playing with our public testnet, the guide for doing that is [here](https://github.com/iov-one/iov-core/blob/master/packages/iov-core/README.md "How to Use IOV-Core").

2. Whether or not you wish to play with our testnet at this time, starring our repos, especially **Weave** and **IOV-Core**, is a great way to stay updated. **Follow these links to view these repos and star them**: [Weave](https://github.com/iov-one/weave "Weave Repository"), [IOV-Core](https://github.com/iov-one/iov-core "IOV-Core Repository").

If you have questions about the project then we encourage you to drop into our Mattermost chat. You can sign up [here](https://t.co/Bb2DBHDLUQ "IOV Community Chat") for the #Community channel, and if you let us know that you're a dev we’ll invite you to our #Developers channel!

# Introduction to IOV

We're building an interoperability solution for the blockchain industry that will be open source and totally decentralized. Our universal wallet with cross chain atomic swaps and human friendly address formats is already a working prototype. This wallet makes using blockchain tokens as easy for regular consumers as sending and receiving email. Our product suite thus solves user experience problems that we believe must be solved in order to bring blockchain tech into mainstream mass adoption. By design, the product suite also offers mutual benefits to key parties in the blockchain ecosystem (not only end users but also blockchain devs, app creators, entrepreneurs, and network miners) in order to facilitate widespread industry adoption.

To briefly introduce the product suite:

**Blockchain Communication Protocol (BCP)** is the standardized protocol that is designed to be backwards and forwards compatible with nearly any blockchain, old or new, to provide all chains interoperability with each other. It is easy to implement and free.

**Blockchain Name Service (BNS)** is our DNS for blockchains. It is used for name asset registration (including human friendly addresses as well as token name definitions for the chains that implement the BCP.

**IOV Wallet** is our universal wallet with cross-chain atomic swaps and human friendly addresses. Both desktop and mobile versions are being built.

**IOV-Core** is the client for the IOV network. It is designed to run in standard JavaScript environments so that third party app developers can build e-commerce payment apps, DEXes, wallets, social media tipping apps, etc. that run in standard web browsers.

**IOV Deployment Tools** are also being developed to enable entrepreneurs to easily create new blockchains that natively implement the BCP. ICOs launched with our tools will natively be able to receive contributions of any token type that is interoperable in IOV's network.

