# Intro-to-blockchain

If you want to learn about web3 and blockchain development then this repo can help you master the technology. This file does not assume your expereince with blockchain development and hence contains material suitable for both begginers and experts. Please use your judgment to find resources relevant to your skill level. Learning is a step-by-step process and diving deep into advanced concepts without a good grasp on fundamentals would never yeild positive results. 

## What is a Blockchain?

A blockchain is a distributed ledger which stores transactions in a decentralized, transparent and immutable way. This video by 3Blue1Brown explains clearly how bitcoin works in a beginner-friendly way.
[How does Bitcoin actually work?](https://youtu.be/bBC-nXj3Ng4)
<br>

There are a lot different blockchains out there but the two most important are:
- [Bitcoin](#bitcoin)
- [Ethereum](#ethereum)

## Bitcoin
The afferomentioned video by 3b1b is a great place to start for anyone wanting to learn about bitcoin. For folks who want to dive deeper into how the technology works should really read [Grokking Bitcoin](https://rosenbaum.se/book/).
<br>
Understanding the [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf) is also important along side GB.
<br>
<br>
This book is perfect for people who want to grasp the cryptography behind how bitcoin works. It does get quite technical after the first few chapters but for anyone wanting to build on any blockchain, it is critical to understand the fundamental workings of bitcoin as it is the inspiration for every blockchain out there.
<br>
<br>
After going through the above resources, you should really play around with a blockchain yourself. [This demo](https://andersbrownworth.com/blockchain/) by Andreas Brownworth is perfect for visualising hashes, blocks, tokens, etc.
<br>
<br>
If you want to learn more about cryptography, you can check out these puzzles on [Cryptohacks](https://cryptohack.org/) and learn about advance concepts like [Elliptic Curve Cryptography](https://blog.cloudflare.com/ecdsa-the-digital-signature-algorithm-of-a-better-internet/) which are fundamental to how bitcoin, ethereum and other blockchains work.
<br>
<br>
Even if you wish to build for Ethereum, every blockchain developer should go through the above resources and understand the fundamental working of bitcon. If you wish to further learn about the bitcoin ecosystem, the next best resource every bitcoin developer should study is [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook) written by Andreas M. Antonopoulos.
<br>
<br>
This amount of knowledge is enough for you to start contributing in open-source projects and apply for programmes like [Summer of Bitcoin](https://www.summerofbitcoin.org/).
<br>
## Ethereum
Bitcoin was created as a decentralised p2p cash system or a 'cryptocurrency'. It was evident that the benefits of a public blockchain could used far beyond just money. Ethereum was developed with the purpose of adding smart contracts onto the blockchain. The EVM is turing complete machine that can run any logic and execute it with the benefits of a blockchain.
<br>
<br>
[Ethereum Foundation](https://ethereum.org/en/learn/) has some great articles on understanding the ecosystem. Along with blogs, reading the [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/) also helps in understadning its differences from bitcoin.
<br>
<br>
Understanding the basics of Ethereum is enough to start Dapp development but the EVM is a very complicated and fascinating machine. As a begginer its recommended to stop here and pick it up again after creating some projects. Speaking of projects, becoming an expert Blockchain developer requires mastery in:
- [Web Development](#web2-resources)
- [Solidity and Web3 Ecosystem](#web3-resources)
- [EVM and Security](#evm-and-security)

### Web2 Resources
***
A Decentralised Application or DApp is just a normal web app with a blockchain like Ethereum serving as its backend. Hence, building a good DApp requires skills in traditional web2 development as well. A DApp consists of smart contracts that can be interacted with through a front-end. Usually these DApps also have backend architechture to handle various SDKs, libraries and even databases.

#### List of Web2 Resources:
1. Basics of HTML, CSS (for building beautiful frontends).
2. JavaScript Basics : Variables, Data Types, if-else blocks, Switch, Loops, Functions, async functions, callbacks : https://www.w3schools.com/js/
3. Node.js basics: node, npm, package.json
4. API and HTTP Requests (GET, POST, PATCH etc..)
5. JavaScript libraries built for integrating ethereum to your frontend like Ethers.js and Web3.js.

Also learning JavaScript frontend frameworks like React.js, Next.js would be great to build more complex applications.


### Web3 Resources
***
The most important component of a DApp is the smart contract. The most popular language to write smart contracts in is [Solidity](https://docs.soliditylang.org/en/v0.8.18/). The best way to learn a new language is through hands-on practice and thats why [CryptoZombies](https://cryptozombies.io/) is recommended as it teaches solidity by building a simple game while explaining various concepts like data-types, arrays, functions, etc. 
<br>
[Solidity by example](https://solidity-by-example.org/) is also a great resource to learn basic syntax and concepts of the language. 
<br>
<br>
By far the most complete and high quality tutorial on Solidity development is by Patrick Collins:
<br>
[32 HOURS FULL BLOCKCHAIN DEVELOPMENT COURSE](https://youtu.be/gyMwXuJrbJQ)
<br>
He also has a video with detailed guidance on [How to become a Blockchain Engineer](https://youtu.be/e1N4aWIJMN0)
<br>
After completing this course you should be able to create any project you can think of. If video tutorials are not your style and you prefer resources similar to crypto zombies then perhaps you can try out [LearnWeb3DAO](https://learnweb3.io/). The Freshmen track is perfect for anyone who has no expereience with blockchain whatsoever. LearnWeb3DAO with a lot of content and is just as good as the course by Patrick Collins.
<br>
<br>
While going through either of the courses (or any other that you prefer) you should also learn about the web3 ecosystem. A basic knowledge of what protocols exist and what they do is critical to understand what problems are present in th ecosystem and how you can fix them.
<br>
These youtube channels have great videos on various topics ranging from DeFi, NFTS, Ethereum protocol, Bitcoin and other blockchains as well.
* [White Board Crypto](https://www.youtube.com/@WhiteboardCrypto)
* [Finematics](https://www.youtube.com/@Finematics)
* [Patrick Collins](https://www.youtube.com/@PatrickAlphaC)
* [Dapp university](https://www.youtube.com/@DappUniversity)
* [Smart Contract Programmer](https://www.youtube.com/@smartcontractprogrammer)
* [Eat the Blocks](https://www.youtube.com/@EatTheBlocks)

Improving your knowledge everyday is the only way to stay ahead in this industry.
<br>
<br>
Knowing about various DeFi protocols and how they work is important. Apart from watching videos from above channels, reading the wHitepapers of popular projects also gives a lot of technical insight into how they function.
* [Uniswap v2](https://uniswap.org/whitepaper.pdf)
* [Compound](https://compound.finance/documents/Compound.Whitepaper.pdf)
* [Aave](https://academy.bit2me.com/wp-content/uploads/2021/07/Aave_Protocol_Whitepaper_v1_0.pdf)
* [Maker DAO](https://makerdao.com/en/whitepaper/)
* [Curve](https://curve.readthedocs.io/_/downloads/en/latest/pdf/)
* [Uniswap v3](https://uniswap.org/whitepaper-v3.pdf)

### EVM and Security
***
Learning solidity is not enough be an expert in writing smart contracts. Deploying and interacting with these contracts require gas, so as a developer you should optimise your code to consume th eleast amount of gas possibel. Also since smart contracts are immutable and transparent, anyone can find vulnerabilities in your code and exploit it. Therefore, making sure that your contract is secure is a top priority for any protocol.
<br>
<br>
In order to write optmised and secure code, a deep knowledge of EVM and security practices is crucial. This field is so vast and technical that the best way to learn is reading blogs and articles from multiple experts. 
Here is a list of a few resources that provide Alpha about the EVM:
* [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook)
* [Noxx](https://noxx.substack.com/)
* [Degatchi](https://degatchi.com/articles)
* [Deconstructing Solidity](https://blog.openzeppelin.com/deconstructing-a-solidity-contract-part-i-introduction-832efd2d7737/)
* [What happens when you send 1 DAI](https://www.notonlyowner.com/learn/what-happens-when-you-send-one-dai)
* [Ethereum Beige paper](https://github.com/chronaeon/beigepaper/blob/master/beigepaper.pdf)
* [Ethereum Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf)

If after accumilating all this Alphs you feel like security and auiditing might be your thing, then you should check out out the [Secureum Bootcamp](https://secureum.substack.com/). Afetr that you can play CTFs and participate in competitions. Here's a list:
* [Ethernaut](https://github.com/ethereumbook/ethereumbook)
* [Capture the Ether](https://capturetheether.com/)
* [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/)
* [Code4rena](https://code4rena.com/)
* [Sherlock](https://www.sherlock.xyz/)
* [Immunefi](https://immunefi.com/)

The best way to learn advanced topics is to learn from the best. The greatest minds in the industry are always active on twitter and ready to help out anyone in need. The crypto community is very collaborative and dont hesitate in sharing information. Here's a list of twitter accounts that provide top tier content:
* [@VitalikButerin](https://twitter.com/VitalikButerin)
* [@bytes032](https://twitter.com/bytes032)
* [@pashovkrum](https://twitter.com/pashovkrum)
* [@HollaWaldfee100](https://twitter.com/HollaWaldfee100)
* [@pcaversaccio](https://twitter.com/pcaversaccio)
* [@tinchoabbate](https://twitter.com/tinchoabbate)
* [@0xOwenThurm](https://twitter.com/0xOwenThurm)
* [@0xRajeev](https://twitter.com/0xRajeev)
* [@StErMi](https://twitter.com/StErMi)
* [@PatrickAlphaC](https://twitter.com/PatrickAlphaC)
* [@pardy_v](https://twitter.com/prady_v)
<br>
The industry is constantly growing and the only way to keep up is constantly learning. This repo is fileld with a lot of resources but there is a lot more content out there that's just as good. If you feel like this repo misses any crucial resources or you'd like to suggest some additional material then feel free to make a Pull Request. Let's keep this resource list active and up to date so it benefits anyone reading this.
<br>
<br>
If you face any doubts regarding any topic then feel free to raise an issue and discuss it with other buidlers. Asking questions is the best way to understand and learn new topics.
<br>
<br>
Happy Learning! WAGMI
