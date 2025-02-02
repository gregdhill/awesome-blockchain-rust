# Awesome Blockchain Rust

*Useful components for building blockchains in Rust. include: cryptography, distributed, p2p, consensus, etc*

- [Blockchains](#blockchains)
- [Blockchain Frameworks](#blockchain-frameworks)
- [Cross-Chain](#cross-chain)
- [Virtual Machines](#virtual-machines)
- [General-Purpose Consensus](#consensus)
- [P2P Network Libraries](#p2p-network-libraries)
- [Cryptography](#cryptography)
- [Layer2](#layer2)
- [Dapps](#dapps)
- [Other](#other)

## Blockchains
- [Bitcoin Cash](https://github.com/be-cash/bitcoin-cash)
A library for creating and parsing Bitcoin Cash trasactions
- [CITA](https://github.com/cryptape/cita) A high performance blockchain kernel for enterprise users;
- [CodeChain](https://github.com/CodeChain-io/codechain) Programmable multi-asset chain;
- [Conflux](https://github.com/Conflux-Chain/conflux-rust) The Rust implementation of Conflux protocol;
- [Darwinia](https://github.com/darwinia-network/darwinia) Relay chain of Darwinia Network, can connect to Polkadot as parachain in Polkadot Model;
- [Enigma](https://github.com/enigmampc/enigma-core) secures the decentralized web;
- [Elrond](https://elrond.com/) Elrond (EGOLD( - scalable and usable blockchain, written is Rust and has smart contracts in Rust
- [Exonum](https://github.com/exonum/exonum) An extensible open-source framework for creating private/permissioned blockchain applications;
- [Forest](https://github.com/ChainSafe/forest) An implementation of Filecoin written in Rust;
- [Grin](https://github.com/mimblewimble/grin) Minimal implementation of the MimbleWimble protocol;
- [Holochain](https://github.com/holochain/holochain-rust) The core Holochain framework written in rust, a container, and hdk-rust library for writing Zomes;
- [Huobi Chain](https://github.com/HuobiGroup/huobi-chain) The next generation high performance public chain for financial infrastructure.
- [Interledger](https://github.com/interledger-rs/interledger-rs) An easy-to-use, high-performance Interledger implementation written in Rust.
- [Libra](https://github.com/libra/libra) global currency and financial infrastructure that empowers billions of people;
- [Lighthouse](https://github.com/sigp/lighthouse) Fast and secure Ethereum 2.0 client;
- [NEAR](https://github.com/nearprotocol/nearcore) NEAR Protocol - scalable and usable blockchain;
- [Nervos CKB](https://github.com/nervosnetwork/ckb) Nervos CKB is a public permissionless blockchain, the common knowledge layer of Nervos network;
- [Nomic](https://github.com/nomic-io/nomic) Nomic is a high-performance Bitcoin sidechain which is part of the Cosmos network.
- [Parity Bitcoin](https://github.com/paritytech/parity-bitcoin) The Parity Bitcoin client;
- [Parity Ethereum](https://github.com/paritytech/parity-ethereum) The fast, light, and robust EVM and WASM client;
- [Parity Zcash](https://github.com/paritytech/parity-zcash) Rust implementation of Zcash protocol;
- [Polkadot](https://github.com/paritytech/polkadot) Polkadot Node Implementation;
- [Shasper](https://github.com/paritytech/shasper) Parity Shasper beacon chain implementation using the Substrate framework;
- [Solana](https://github.com/solana-labs/solana) Blockchain Rebuilt for Scale;
- [Stacks 2.0](https://github.com/blockstack/stacks-blockchain) Proof of Transfer blockchain from Blockstack;
- [Tari](https://github.com/tari-project) The Tari Digital Assets Protocol;
- [Tendermint](https://github.com/informalsystems/tendermint-rs) Tendermint is a high-performance blockchain consensus engine for Byzantine fault tolerant applications 
- [Witnet](https://github.com/witnet/witnet-rust) Open source implementation of Witnet decentralized oracle network protocol in Rust;
- [Zebra](https://github.com/ZcashFoundation/zebra) An ongoing Rust implementation of a Zcash node.
- [Zero-chain](https://github.com/LayerXcom/zero-chain) A privacy-preserving blockchain on Substrate.
- [zkSync](https://github.com/matter-labs/zksync) Matter Labs' scaling L2 engine secured by zero-knowledge proofs.

## Blockchain Frameworks
- [Substrate](https://github.com/paritytech/substrate) Substrate: The platform for blockchain innovators;
- [slingshot](https://github.com/stellar/slingshot) A new blockchain architecture under active development, with a strong focus on scalability, privacy and safety.
- [Tendermint ABCI](https://github.com/tendermint/rust-abci) Tendermint ABCI server, written in the Rust programming language.
- [Orga](https://github.com/nomic-io/orga) A high-performance state machine engine designed for Tendermint-based blockchain applications.

## Cross-Chain
- [Comit](https://comit.network/) is an open protocol facilitating trustless cross-blockchain applications.
- [IBC](https://github.com/informalsystems/ibc-rs) Rust implementation of the Interblockchain Communication Protocol (IBC).

## Virtual Machines
- [CKB-VM](https://github.com/nervosnetwork/ckb-vm) -- RISC-V virtual machine;
- [CosmWasm](https://www.cosmwasm.com) -- Multi-chain smart contract platform built for the Cosmos ecosystem;
- [EVM Parity](https://github.com/paritytech/parity-ethereum/tree/master/evmbin) -- Parity implementation of EVM;
- [SVM](https://github.com/spacemeshos/svm) -- Spacemesh Virtual Machine;
- [Wasmi](https://github.com/paritytech/wasmi) -- WebAssembly interpreter;
- [Wasmer](https://wasmer.io/) -- a convenient Rust wrapper over WebAssembly backends;
- [Wasmtime & Lightbeam](https://github.com/CraneStation/wasmtime) -- Wasmtime -- JIT runtime, Lightbeam -- single-pass compiler for WebAssembly.

## General-Purpose Consensus
- [Raft](https://github.com/pingcap/raft-rs) Raft distributed consensus algorithm implemented in Rust;
- [parsec](https://github.com/maidsafe/parsec) Protocol for Asynchronous, Reliable, Secure and Efficient Consensus;
- [Honey Badger](https://github.com/poanetwork/hbbft) An implementation of the paper "Honey Badger of BFT Protocols" in Rust.

## P2P Network Libraries
- [chamomile](https://github.com/placefortea/chamomile) p2p implement on Actor. Everything is for ease of use;
- [crust](https://github.com/maidsafe/crust) Reliable p2p network connections in Rust with NAT traversal. One of the most needed libraries for any server-less / decentralised projects;
- [libp2p](https://github.com/libp2p/rust-libp2p) The Rust Implementation of libp2p networking stack;
- [p2p](https://github.com/driftluo/p2p) A multiplexed p2p network framework that supports custom protocols; (漂流)
- [p2p](https://github.com/ustulation/p2p) NAT Traversal techniques for p2p communication; (Spandan Sharma)
- [quic-p2p](https://github.com/maidsafe/quic-p2p) peer-to-peer communications library for Rust based on QUIC protocol;
- [rckad](https://github.com/rust-cc) Efficient and flexible S/Kademlia implementation;
- [routing](https://github.com/maidsafe/routing) Routing - specialised storage DHT.

## Cryptography
- [Awesome Cryptography Rust](https://github.com/rust-cc/awesome-cryptography-rust);
- [Dalek Cryptography](https://github.com/dalek-cryptography);
- [Za!](https://github.com/adria0/za) -- An experimental rust zksnarks compiler with embeeded bellman-bn128 prover;
- [OpenZKP](https://github.com/0xProject/OpenZKP) -- Pure Rust implementations of Zero-Knowledge Proof systems.

## Layer2
- [Rust-Lightning](https://github.com/rust-bitcoin/rust-lightning)
  is a Bitcoin Lightning library written in Rust.
  The main crate, lightning, does not handle networking,
  persistence, or any other I/O. Thus, it is runtime-agnostic,
  but users must implement basic networking logic,
  chain interactions, and disk storage.

## Dapps
- [Serum-dex](https://github.com/project-serum/serum-dex).
A decentralized exchange built on Solana.

## Other
- [abscissa](https://github.com/iqlusioninc/abscissa) -- micro-framework for CLI tools with strong focus on security;
- [tesseracts](https://github.com/adria0/tesseracts) -- A small block explorer for geth PoAs written in rust.
- [merk](https://github.com/nomic-io/merk) -- High performance Merkle key/value store written in Rust, based on RocksDB.


## Contribute
Contributions are most welcome. 

GitHub: [Awesome Blockchain Rust](https://github.com/rust-in-blockchain/awesome-blockchain-rust)


## License
[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
