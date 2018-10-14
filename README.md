# Welcome to IOV

We'll point you to the docs and repos you need to get started: first, this README contains a "How to Get Started" section and further below, we have included a brief introduction to IOV for those not already familiar with the project. 

IOV is working on making life easier for blockchain users. 

We are providing a Blockchain Name Service which is a register for names used in the blockchain ecosystem, such as personal value addresses, asset names, blockchain names for developers or companies. We believe naming things makes them easier to use for everyone. 

We are also providing a toolkit to build apps that can easily use and swap all assets from all blockchains. We believe the future of apps is there.

Enjoy and please send us feedback !

# How to Get Started

We are building technology to **run a blockchain of names**, the BNS, and build clients for our blockchain. The code to do this is in [Weave](https://github.com/iov-one/weave "Weave Repository"). You can run a validator of the blockchain [here](https://github.com/iov-one/sandbox/wiki/Validator "Validator") and you can build a client to the blockchain by using [iov-cli](https://github.com/iov-one/iov-core/blob/master/packages/iov-cli/README.md "IOV-Client Repository").

We are also building a technology that allows you to **build apps that can access all blockchains**. We are still at the beginning, but you can start building an app that works with Tendermint, Lisk and Rise at the moment, soon ethereum, by using our library **iov-core**. Click [here](https://iov-one.github.io/iov-core-docs/latest/iov-core/index.html "How to Use IOV-Core") to get started.

We have built the first app with iov-core, the **IOV Wallet**, and you can see how iov-core is used and adapted for UI via BCP-Redux. You can use the adaptor from IOV-Core to Redux here: [BCP-redux](https://github.com/iov-one/bcp-redux "BCP-redux repository") and the specific implementation of the [IOV-Wallet](https://github.com/iov-one/iov-wallet "IOV Wallet Repository") (still work in progress, watch it).

Finally, if you are running a blockchain technology and want **to be compatible with IOV-Core**, we will release full BCP specifications soon. In the meantime, you can start looking at our [code](https://github.com/iov-one/iov-core/tree/master/packages/iov-bns "Codec") and our [documentation](https://iov-one.github.io/iov-core-docs/latest/iov-core/index.html "How to Use IOV-Core") to get familiar with how it all works.

You're free to explore the GitHub, all feedback is welcome!

# Get in touch, give feedback and ask questions

If you have questions about the project then we encourage you to drop into our Mattermost chat. You can sign up [here](https://t.co/Bb2DBHDLUQ "IOV Community Chat") for the #Community channel, and if you let us know that you're a dev we’ll invite you to our #Developers channel!

# Introduction to IOV

We're building an interoperability solution for the blockchain industry that will be open source and totally decentralized. Our universal wallet with cross chain atomic swaps and human friendly address formats is already a working prototype. This wallet makes using blockchain tokens as easy for regular consumers as sending and receiving email. Our product suite thus solves user experience problems that we believe must be solved in order to bring blockchain tech into mainstream mass adoption. By design, the product suite also offers mutual benefits to key parties in the blockchain ecosystem (not only end users but also blockchain devs, app creators, entrepreneurs, and network miners) in order to facilitate widespread industry adoption.

To briefly introduce the product suite:

**Blockchain Communication Protocol (BCP)** is the standardized protocol that is designed to be backwards and forwards compatible with nearly any blockchain, old or new, to provide all chains interoperability with each other. It is easy to implement and free.

**Blockchain Name Service (BNS)** is our DNS for blockchains. It is used for name asset registration (including human friendly addresses as well as token name definitions for the chains that implement the BCP.

**IOV Wallet** is our universal wallet with cross-chain atomic swaps and human friendly addresses. Both desktop and mobile versions are being built.

**IOV-Core** is the client for the IOV network. It is designed to run in standard JavaScript environments so that third party app developers can build e-commerce payment apps, DEXes, wallets, social media tipping apps, etc. that run in standard web browsers.

**IOV Deployment Tools** are also being developed to enable entrepreneurs to easily create new blockchains that natively implement the BCP. ICOs launched with our tools will natively be able to receive contributions of any token type that is interoperable in IOV's network.

