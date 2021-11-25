# Awesome-Nervos-CKB
A collection of Nervos CKB Resources.



# Table of Contents
- [Core Material and Documentation](#core-material-and-documentation)
- [Tools](#tools)
  - [IDEs](#ides)
  - [SDKs](#sdks)
  - [Wallets](#wallets)
  - [Frameworks](#frameworks)
  - [Ecosystem Projects](#ecosystem-projects)
  - [On-Chain Scripts and Protocols](#on-chain-scripts-and-protocols)
  - [NFT Resources](#nft-resources)
  - [Experimental Projects and Demos](#experimental-projects-and-demos)
  - [Other](#other)
- [Dapps](#dapps)
  - [Tutorials](#tutorials)
  - [Example Dapps](#example-dapps)
- [Tokens & Assets](#tokens-and-assets)
  - [Standards](#standards)
- [Community and Social](#community-and-social)
  - [Multimedia](#multimedia)
  - [Developer Support](#developer-support)
  - [News and Updates](#news-and-updates)



## Core Material and Documentation
- [Nervos Docs](https://docs.nervos.org/)
- [RFCs](https://github.com/nervosnetwork/rfcs)
- [Medium Articles](https://medium.com/nervosnetwork)



## Tools

### IDEs
- [CKB Studio. An IDE to develop CKB scripts on the Nervos blockchain + Tutorials](https://github.com/ObsidianLabs/CKB-Studio) // [Obsidians Labs](https://www.obsidians.io/)
- [ChainIDE. A Cross-Chain Dapp Development IDE Platform for Nervos](https://chainide.com/s/nervos/)

### SDKs
- [Go SDK](https://github.com/ququzone/ckb-sdk-go)
- [Java SDK](https://github.com/nervosnetwork/ckb-sdk-java)
- [JavaScript SDK](https://github.com/nervosnetwork/ckb-sdk-js)
- [JavaScript Toolkit](https://github.com/xxuejie/ckb-js-toolkit) and [JavaScript Toolkit Addons](https://github.com/xxuejie/ckb-js-toolkit-contrib)
- [Ruby SDK](https://github.com/nervosnetwork/ckb-sdk-ruby), [CKB Ruby Scripts](https://github.com/nervosnetwork/ckb-ruby-scripts) and [CKB Ruby SDK Demo](https://github.com/nervosnetwork/ckb-demo-ruby)
- [Dart SDK](https://github.com/duanyytop/ckb_sdk_dart)
- [CKB Python Toolkit](https://github.com/duanyytop/ckb-python-toolkit)
- [Python SDK. Not an official SDK. The project is still in an early stage. Unstable](https://github.com/doitian/ckb-sdk-python)
- [CKB Kotlin SDK](https://github.com/BlueWatson/ckb-sdk-kotlin)
- [CKB Swift Kit](https://github.com/duanyytop/ckb-swift-kit) and [CKB Swift SDK](https://github.com/xiaoluSF/ckb-sdk-swift)

### Wallets
- [Neuron](https://github.com/nervosnetwork/neuron)

### Frameworks
- [GodWoken: Programmable Account Layer on Top of Nervos CKB](https://github.com/jjyr/godwoken)
    - [Godwoken Examples](https://github.com/nervosnetwork/godwoken-examples)
    - [Godwoken SDK JS](https://github.com/nervosnetwork/godwoken-js-sdk)
    - [Godwoken-Polyjuice compatible providers for ethereum library like ethers and web3js.](https://github.com/nervosnetwork/polyjuice-provider)
- [Muta: A Framework for Building Layer 2 Chains](https://github.com/nervosnetwork/muta)
    - [Muta SDK Rust](https://github.com/nervosnetwork/muta-sdk-rust)
    - [Muta SDK JS/TS](https://github.com/nervosnetwork/muta-sdk-js)
    - [Muta SDK Java](https://github.com/nervosnetwork/muta-sdk-java)
    - [Drone. Standard Tooling for Muta framework](https://github.com/nervosnetwork/drone)
    - [Hermit Purple. A GraphQL API server for Muta framework](https://github.com/huwenchao/hermit-purple-server)
- [Lumos: Full Featured Dapp Framework for Javascript/Typescript](https://github.com/nervosnetwork/lumos)
- [Capsule: Framework for Developing CKB Contracts in Rust](https://github.com/nervosnetwork/capsule)
- [Tentacle: A multiplexed p2p network framework that supports custom protocols](https://github.com/nervosnetwork/tentacle)

### Ecosystem Projects
- [ABC Wallet: Web Auth SDK -- In Development](https://talk.nervos.org/t/abc-wallet-another-ckb-sdk-and-ckb-web-auth/4285/2)
- [Synapse: Wallet Browser Extension -- In Development](https://talk.nervos.org/t/synapse-browser-wallet-and-keyper-agency/4339/3)
    - [Synapse Extension Github](https://github.com/rebase-network/synapse-extension)
- [PW-SDK: An interoperability dApp framework. Allow wallets designed for other chains to be used on Nervos](https://talk.nervos.org/t/lay2-pw-sdk-build-dapps-on-ckb-and-run-them-everywhere/4289/12)
    - [Documentation Gitbook](https://docs.lay2.dev/pw-sdk/)
- [ZKP-Toolkit-CKB: A Zero Knowledge Proof Toolkit for CKB -- In Development](https://talk.nervos.org/t/secbit-labs-zkp-toolkit-ckb-a-zero-knowledge-proof-toolkit-for-ckb/4254/1)
    - [Zero-knowledge proofs toolkit for CKB Github](https://github.com/sec-bit/ckb-zkp)
- [SUMMA: Bitcoin-SPV. A set of libraries for working with Bitcoin from other chains](https://talk.nervos.org/t/summa-bitcoin-spv-utils/4162)
    - [Bitcoin SPV C code for Nervos Github](https://github.com/summa-tx/bitcoin-spv/tree/master/c)
- [Trampoline: Fullstack development framework for UTXO-based dapps on Nervos Network. Early-stage, pre-alpha development](https://github.com/WilfredTA/trampoline-rs)
- [YokaiSwap. First Cross-chain DEX AMM on Nervos](https://github.com/YokaiSwap)
- [Unipass. A multi-chain unified crypto identity and your universal passport to crypto world and metaverse](https://docs.unipass.id/)
    -  [Lay2dev's Github. Unipass and PW-SDK developers](https://github.com/orgs/lay2dev/repositories)
- [Mibao. NFT Marketplace](https://github.com/orgs/nervina-labs/repositories)
- [Decentralized Account Systems DAS](https://github.com/DeAccountSystems)
- Nervos Hackathon: Broaden the Spectrum Projects:
    - [CrowdMint by niklr. A blockchain based solution leveraging NFTs to crowdfund community projects](https://github.com/niklr/crowdmint)
    - [Insure Defi by chaitanyasjoshi. Offers collateral protection insurance for crypto-backed loans](https://github.com/chaitanyasjoshi/nervos-insure)
    - [Fomaj by irshadnilam. Formaj is a risk-free prediction marketing inspired by PoolTogether and Pancakeswap Predictions](https://github.com/fomaj)
    - [Godwoken Balance Tracker by nicoderpro](https://github.com/NiCoderPro/godwoken_tracker)
    - [LinoB Vault by jpeterd. A platform that offers users a way to stabilize value on the Nervos Layer 2 chain using the LinoB USD pegged stablecoin](https://github.com/LinoB-Vault/LinoB-Vault-Main)
    - [NolayReading. Pay for Reading NFT by pandatea](https://github.com/nolaytech/NolayReading)
    - [Backable by luisantoniocrag. A decentralized and collateralized stablecoin protocol with a value pegged to the US dollar on the Nervos network](https://github.com/Backable)
    - [Nervos Hackathon Dex by fsy412](https://github.com/fsy412/Nervos-Hackathon-Dex)
    - [Nerbot by x777. The Nerbot is a telegram NFT marketplace bot for the Nervos Network blockchain](https://github.com/x777/Nerbot)

### On-Chain Scripts and Protocols
- [Anyone Can Pay: A lock script that allows cells to accept tokens from anyone](https://github.com/nervosnetwork/ckb-anyone-can-pay)
- [CKB System Scripts: Hardcoded scripts in the Nervos CKB genesis block](https://github.com/nervosnetwork/ckb-system-scripts)
- [CKB Production Scripts. CKB scripts used in production.](https://github.com/nervosnetwork/ckb-production-scripts)
- [DCKB: Wrapper Token for DAO Deposited CKBytes](https://github.com/jjyr/DCKB)
- [Growfi: On-chain User Defined Token Swap](https://talk.nervos.org/t/growfi-udt-swap/4382/8)
- [Miscellanneous Scripts (Simple User Defined Token, HTLC, Dynamic Linking)](https://github.com/nervosnetwork/ckb-miscellaneous-scripts)
- [On-chain scripts of Godwoken project](https://github.com/nervosnetwork/godwoken-scripts)

### NFT Resources
- [RFC: CKB NFT (Draft Spec). Token Development & CKB Programming Model](https://talk.nervos.org/t/rfc-ckb-nft-draft-spec/4779)
- [RFC: Multi-Token Extensible NFT (Draft Spec)](https://talk.nervos.org/t/rfc-multi-token-extensible-nft-draft-spec/5019)
- [Compact Extension for m-NFT Protocol: The Key to Mass Adoption](https://talk.nervos.org/t/compact-extension-for-m-nft-protocol-the-key-to-mass-adoption/6249)
    - [Compact m-NFT. A compact m-NFT contract for Nervos CKB](https://github.com/xcshuan/compact-mNFT)
    - [The sparse merkle tree data structure of compact-NFT](https://github.com/nervina-labs/compact-nft-smt)
    - [Example of CKB NFT SMT](https://github.com/duanyytop/nft-smt-example)
- [CKB NFT Toolkit. A toolkit who provides methods to create, transfer, update and destroy issuer cells, class cells and NFT cells of Nervos CKB](https://github.com/duanyytop/ckb-nft-toolkit)
- [CKB NFT Extension](https://github.com/duanyytop/ckb-nft-extension)
- [Dynamic Interation Extension for m-NFT Protocol](https://talk.nervos.org/t/dynamic-interaction-extension-for-m-nft-protocol/6063)
- [RFC: Multi-purpose NFT Draft Spec](https://talk.nervos.org/t/rfc-multi-purpose-nft-draft-spec/5434)
    - [The NFT Type Scripts implement of RFC: Multi-purpose NFT Draft Spec on Nervos CKB](https://github.com/nervina-labs/ckb-nft-scripts)
- [NFT Open API Demo Python](https://github.com/nervina-labs/nft_open_api_demo_python)
- [DID solution on Nervos based on mNFT protocol](https://talk.nervos.org/t/did-solution-on-nervos-based-on-mnft-protocol/5651)

### Experimental Projects and Demos
- [CKB Simple Account Layer](https://github.com/xxuejie/ckb-simple-account-layer)
- [Keyper: Ownership Layer for Managing Lockscripts on Nervos CKB](https://github.com/ququzone/keyper)
- [CKB NFT Kabletop](https://github.com/duanyytop/ckb-nft-kabletop)
- [Minimal CKB Sudt Dapp Demo](https://github.com/huwenchao/ckb-sudt-dapp-demo)
- [Godwoken Uniswap Example](https://github.com/huwenchao/godwoken-uniswap-example)
- [A simplified ETH bridge contract demo to show how to mint SUDT on CKB](https://github.com/huwenchao/mint-sudt-demo)
- [This is a simple example to show how to use CKB crates in C via FFI.](https://github.com/jjyr/ckb-ffi)

### Other
- [One-click way to create testnet and mainnet layer 2 accounts using MetaMask](https://dev.ckb.tools/create-layer2-account)
- [Animagus: An accounting layer for Nervos](https://github.com/xxuejie/animagus)
    - [Mandrake: A GUI for Animagus](https://github.com/nervosnetwork/mandrake)
- [CKB Explorer: A Nervos blockchain explorer](https://explorer.nervos.org/)
- [CKB UDT CLI: Command line tool to create SUDT tokens](https://github.com/ququzone/ckb-udt-cli)
- [Molecule: A serialization library for Rust](https://github.com/nervosnetwork/molecule)
    - [Molecule Javascript](https://github.com/Keith-CY/molecule-javascript)
    - [Molecule Javascript Template: It shows the most general way of using molecule-javascript in Browsers and Node.js with real-world demos](https://github.com/keith-cy/molecule-javascript-template)
- [Mercury. Building on top of ckb-indexer, Mercury provides handy integration features for Nervos CKB.](https://github.com/nervosnetwork/mercury)
- [Force Bridge. Can connect to all chains which support multiple signature account and Non-fungible token transfer](https://github.com/nervosnetwork/force-bridge)
    - [Force Bridge User Interface](https://github.com/nervosnetwork/force-bridge-ui)
    - [Force Bridge ETH](https://github.com/nervosnetwork/force-bridge-eth)
- [Tippy One click CKB devnet. Tippy is pre-built as self-contained .Net Core application.](https://github.com/nervosnetwork/tippy)
- [Polyjuice: An Ethereum compatible account layer for Nervos](https://github.com/nervosnetwork/polyjuice)



## Dapps

### Tutorials
- [CKB Script Programming Series](https://xuejie.space/)
- [Developer Training Course. Best place to start learning about Layer 1 code development](https://nervos.gitbook.io/developer-training-course/)
- [Godwoken Gitbook Guide: a optimistic rollup solution build upon Nervos CKB](https://docs.godwoken.io/)
- [Layer 2 EVM (Ethereum Virtual Machine) Training. Tasks from Nervos Hackaton DeFi](https://nervos.gitbook.io/layer-2-evm/)
- [Working with CKB Studio Series](https://medium.com/nervos-ckb-israel)
- VideoTutorials
    - [Video: Porting Your First EVM Solidity Application To Nervos Blockchain](https://www.youtube.com/watch?v=5GLX2i2bK_0)
    - [Video: Making Nervos Development Work For You With Docker](https://www.youtube.com/watch?v=xx_fyMiFEfs)
    - [Video: Tools Your Know: React and Web3.js for Nervos Dapps](https://www.youtube.com/watch?v=BmQBv4VRUjI)
    - [Video: Integrating Duktape JS VM into EVM Layer 2 with Retric Su](https://www.youtube.com/watch?v=Y5NhmaNBCxE)
    - [Video: Understanding the Token Sale Lock Script](https://www.youtube.com/watch?v=ysUbx4FAKlE)


### Example Dapps
- [Gringotts: Token Renting](https://github.com/ashchan/gringotts)
- [Token Mint: Issue Tokens in Browser](https://github.com/WilfredTA/token_mint)



## Tokens and Assets

### Standards
- Simple UDT (SUDT): A simple user defined token standard similar to ERC20
    - [Standard](https://talk.nervos.org/t/rfc-simple-udt-draft-spec/4333/4)
    - [C Implementation](https://github.com/nervosnetwork/ckb-miscellaneous-scripts/blob/master/c/simple_udt.c) 
    - [Rust Implementation -- In Development](https://github.com/jjyr/my-sudt/blob/master/contracts/my-sudt/src/main.rs)

- Extensible UDT(xUDT): an extension on Simple UDT
    - [RFC: Extensible UDT](https://talk.nervos.org/t/rfc-extensible-udt/5337)
    - [RFC: Regulation Compliance Extension](https://talk.nervos.org/t/rfc-regulation-compliance-extension/5338)
    - [Discussion on the regulatory extension to sUDT](https://talk.nervos.org/t/discussion-on-the-regulatory-extension-to-sudt/5060)


## Community and Social

### Multimedia
- [Nervos Network Medium Publication](https://medium.com/nervosnetwork)
- [Nervos Network YouTube Channel](https://youtube.com/nervosnetwork)

### Developer Support
- [Discord Chatroom](https://discord.gg/AqGTUE9)
- [Telegram Chatroom](https://t.me/nervos_ckb_dev)
- [Nervos Forums](https://talk.nervos.org/)

### News and Updates
- [Nervos Newsletter (Bottom of Page)](https://www.nervos.org/)
- [Nervos Twitter](https://twitter.com/NervosNetwork)
