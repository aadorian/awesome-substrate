![Substrate Logo](substrate_logo_dark.png)

# Awesome Substrate

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> An awesome list is a list of awesome things curated by the community.

-[GitHub Topics: Awesome Lists](https://github.com/topics/awesome-list)

This is the official **Awesome List** for Substrate, it is maintained by the Substrate Developer Hub
team.

## Contents

- [What is Substrate](#what-is-substrate)
- [Official Resources](#official-resources)
- [Recordings](#recordings)
- [Workshops & Demos](#workshops--demos)
- [Community Resources](#community-resources)
  - [Community Resources - Guides](#community-resources---guides)
- [Frameworks](#frameworks)
- [Templates](#templates)
- [Pallets](#pallets)
- [Client Libraries](#client-libraries)
- [Ecosystem Tools](#ecosystem-tools)
- [Alternative Implementations](#alternative-implementations)
- [SCALE Codec](#scale-codec)
  - [SCALE Codec - Implementations](#scale-codec---implementations)

## What is Substrate

Substrate is a framework for building upgradable, modular and efficient blockchains. Substrate is an
open-source library of [Rust](https://www.rust-lang.org/) code that is maintained by
[Parity Technologies](https://www.parity.io/).

## Official Resources

- [substrate.io](https://substrate.io/) - Product page.
- [Developer Hub](https://substrate.dev/) - Developer portal.
  - [Tutorials](https://substrate.dev/tutorials) - Guided exercises to get you started.
  - [Knowledge Base](https://substrate.dev/knowledgebase) - In-depth documentation related to
    Substrate development.
  - [Recipes](https://substrate.dev/recipes) - Working code examples that solve common problems.
  - [Reference Docs](https://substrate.dev/rustdocs) - Rustdoc API documentation.
- [Seminar](https://substrate.dev/seminar) - Collaborative learning on
  [Crowdcast](https://www.crowdcast.io/e/substrate-seminar)
- [Technical Chat](https://app.element.io/#/room/!HzySYSaIhtyWrwiwEV:matrix.org) - Ask questions &
  chat with other Substrate developers.
- [Builders Program](https://www.substrate.io/builders-program) - White-glove support for visionary
  teams.
- [Web3 Foundation Grants](https://web3.foundation/grants) - Funding for ecosystem development.
- [Users](https://www.substrate.io/substrate-users) - Teams building with Substrate.
- [GitHub](https://github.com/paritytech/substrate) - Substrate source code.
- [Developer Hub GitHub](https://github.com/substrate-developer-hub/) - Developer Hub repositories.
- [Polkadot GitHub](https://github.com/paritytech/polkadot) - Substrate monorepo for multiple
  Parity-sponsored chains.
- [Parity Blog](https://www.parity.io/blog/) - Read about updates in the Substrate ecosystem.
- [Twitter](https://twitter.com/substrate_io) - Follow us to stay up-to-date.
- [Polkassembly](https://polkassembly.io/) - The place to discuss and vote on Kusama and Polkadot
  governance.

## Recordings

- [Introduction to Substrate](https://www.crowdcast.io/e/ocimgwg2)
- [Parachains, Cumulus & the Rococo Test Network](https://www.crowdcast.io/e/zpnjlj0r)
- [Enterprise Demo](https://www.crowdcast.io/e/substrate-seminar/6)
- [Bridges & Cross-Chain Interoperability](https://www.crowdcast.io/e/substrate-seminar/12)
- [Archive Indexing Engine](https://www.crowdcast.io/e/substrate-seminar/15)
- [Ethereum Apps on Substrate Chains](https://www.crowdcast.io/e/ethereum-apps-moonbeam)
- [Polkadot Network Technical Explainers](https://www.youtube.com/playlist?list=PLOyWqupZ-WGuAuS00rK-pebTMAOxW41W8)
- [Sub0 Developer Conference](https://www.crowdcast.io/e/axvfinsv)

## Workshops & Demos

- [UTXO Workshop](https://github.com/substrate-developer-hub/utxo-workshop) - Use Substrate to
  implement a Bitcoin-like chain.
- [Cumulus Wokshop](https://substrate.dev/cumulus-workshop/#/) - Build a parachain with Cumulus.
- [Enterprise Sample](https://github.com/substrate-developer-hub/substrate-enterprise-sample) - A
  fully-featured sample that uses a supply chain use case to demonstrate Substrate's rich set of
  capabilities.

## Community Resources

- [DotLeap](https://dotleap.com/) - Community content and newsletter.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/substrate) - Questions tagged
  `substrate`.
- [Reddit](https://www.reddit.com/r/substrate/) - Official subreddit.
- [Polkadot Stack](https://github.com/w3f/General-Grants-Program/blob/master/grants/polkadot_stack.md) - Another
  awesome list maintained by our friends at [Web3 Foundation](https://web3.foundation/).
- [Subsocial](https://subsocial.network/) - Decentralized social network for the Polkadot / Kusama
  ecosystem. Built on Substrate + IPFS.
- [DOTspot](https://www.dotspot.io/) - An open-place for Substrate ecosystem projects to share their
  latest news.

### Community Resources - Guides

- [Build Substrate in a few minutes at a low cost](https://medium.com/@yangWao/build-substrate-in-few-minutes-with-fraction-costs-26fce6aa5066) - Guide
  to using [`cargo remote`](https://github.com/sgeisler/cargo-remote) and [Google Cloud](https://cloud.google.com/) to
  reduce Substrate build times; written by Substrate community member [Matej Nemček](https://medium.com/@yangWao).

## Frameworks

- [FRAME](https://substrate.dev/docs/en/knowledgebase/runtime/frame) - An idiomatic system for
  building Substrate runtimes.
- [ink!](https://github.com/paritytech/ink) - Smart contract language for Substrate chains.
- [Cumulus](https://github.com/paritytech/cumulus) - Simplified Polkadot-compatible parachains.
- [Bridges](https://github.com/paritytech/parity-bridges-common) - A collection of tools for
  cross-chain communication.
- [Frontier](https://github.com/paritytech/frontier) - End-to-end Ethereum emulation for Substrate
  chains.
- [Polkadot-JS](https://polkadot.js.org/) - Rich framework for front-end development.
- [SubstraTEE](https://www.substratee.com) - Trusted off-chain execution framework that uses
  [Intel SGX](https://en.wikipedia.org/wiki/Software_Guard_Extensions) trusted execution
  environments.
- [FRAME Benchmarking](https://github.com/paritytech/substrate/tree/master/frame/benchmarking) - The
  official benchmarking framework for the FRAME system for runtime development.

## Templates

- [Node](https://github.com/substrate-developer-hub/substrate-node-template) - A fresh FRAME-based
  node, ready for hacking.
- [Pallet](https://github.com/substrate-developer-hub/substrate-pallet-template) - Easily create
  pluggable blockchain capabilities.
- [Parachain](https://github.com/substrate-developer-hub/substrate-parachain-template) - A new
  Cumulus-based Substrate node, ready for hacking (see 'Cumulus' under Frameworks for more info).
- [Front-End](https://github.com/substrate-developer-hub/substrate-front-end-template) - Use the
  Polkadot-JS API and [React](https://reactjs.org/) to build front-ends for Substrate-based chains.

## Pallets

- [Open Runtime Module Library (ORML)](https://github.com/open-web3-stack/open-runtime-module-library) - Community
  maintained collection of Substrate runtime modules.
- [Sunshine Bounty](https://github.com/sunshine-protocol/sunshine-bounty/tree/master/pallets) - Distributed
  autonomous organization (DAO) for administering a bounty program.
- [Sunshine Identity](https://github.com/sunshine-protocol/sunshine-keybase/tree/master/identity/pallet) - Keybase-inspired
  identity management.
- [Sunshine Faucet](https://github.com/sunshine-protocol/sunshine-keybase/tree/master/faucet/pallet) - Dispense
  resources for a development chain.
- [Commodities](https://github.com/danforbes/pallet-nft) - Defines and implements a non-fungible
  token interface.

## Client Libraries

- [`subxt`](https://github.com/paritytech/substrate-subxt) - Official Rust client.
- [Substrate API Client](https://github.com/scs/substrate-api-client) - Rust client maintained by
  [Supercomputing Systems AG](https://www.scs.ch/).
- [Polkadot-JS API](https://github.com/polkadot-js/api/) - Semi-official JavaScript library for
  Substrate-based chains.
- [Python Substrate Interface](https://github.com/polkascan/py-substrate-interface) - Maintained by
  [Polkascan Foundation](https://polkascan.org/).
- [Go Substrate RPC Client](https://github.com/centrifuge/go-substrate-rpc-client/) - Maintained by
  [Centrifuge](https://centrifuge.io/).
- [Substrate C++ API](https://github.com/usetech-llc/polkadot_api_cpp) - Maintained by
  [Usetech](https://usetech.com/blockchain/).
- [Substrate .Net API](https://github.com/usetech-llc/polkadot_api_dotnet) - Maintained by Usetech.
- [SubstrateNetApi](https://github.com/darkfriend77/SubstrateNetApi) - Maintained by Substrate community member Cedric
  Decoster ([@darkfriend77 on GitHub](https://github.com/darkfriend77)).

## Ecosystem Tools

- [Polkadot-JS Apps UI](https://polkadot.js.org/apps/) - Semi-official block explorer & front-end
  for Substrate-based chains.
- [Polkadot-JS Extension](https://github.com/polkadot-js/extension) - Browser extension for
  interacting with Substrate-based chains.
- [Sidecar](https://github.com/paritytech/substrate-api-sidecar) - REST service that runs alongside
  Substrate nodes.
- [Archive](https://github.com/paritytech/substrate-archive) - Indexing engine for Substrate chains.
- [TxWrapper](https://github.com/paritytech/txwrapper) - Helpful library for offline transaction
  creation.
- [Subkey](https://substrate.dev/docs/en/knowledgebase/integrate/subkey) - Command line utility for
  working with cryptographic keys.
- [Polkascan](https://polkascan.io/) - Multi-chain block explorer maintained by Polkascan
   Foundation.
- [VSCode Substrate](https://marketplace.visualstudio.com/items?itemName=paritytech.vscode-substrate) - Official
  plugin for Visual Studio Code.
- [Parity Signer](https://www.parity.io/signer/) - Upcycle an unused mobile phone into an air-gapped
  hardware wallet.
- [Fork Off Substrate](https://github.com/maxsam4/fork-off-substrate) - Script to help bootstrap a
  new chain with the state of a running chain.
- [Substrate debug-kit](https://github.com/paritytech/substrate-debug-kit) - A collection of tools
  and libraries for debugging Substrate-based chains, including
  [`offline-election`](https://github.com/paritytech/substrate-debug-kit/tree/master/offline-election),
  which is a tool that is used to predict nominated proof-of-stake elections.
- [`sup`](https://github.com/clearloop/sup) - Command line tool for generating or upgrading a
  Substrate node.
- [Substrate Dev Hub Utils](https://github.com/danforbes/substrate-devhub-utils) - _Unofficial_
  utilities for working with official Substrate Developer Hub resources.
- [Subscan](https://www.subscan.io/) - Multi-network explorer for Substrate-based chains.
- [Substrate Docker Builders](https://github.com/ETeissonniere/substrate-nodeops) - A set of
  Dockerfiles and GitHub Actions to auto-build and push a Docker image for Substrate-based chains.
- [Halva](https://github.com/halva-suite/halva) - A toolchain for improving the experience of
  developing on Substrate.
- [`offchain::ipfs`](https://rs-ipfs.github.io/offchain-ipfs-manual/) - Substrate infused with
  [IPFS](https://ipfs.io/).

## Alternative Implementations

- [Gossamer](https://gossamer.chainsafe.io/) - A Polkadot client implemented in Go; from
  [ChainSafe](https://chainsafe.io/).
- [Kagome](https://kagome.readthedocs.io/en/latest/) - A C++17 implementation of the Polkadot client;
  from [Soramitsu](http://www.soramitsu.co.jp/).
- [LimeChain AssemblyScript Runtime](https://github.com/LimeChain/as-substrate-runtime) - An
  account-based Substrate proof-of-concept runtime written in AssemblyScript; from
  [LimeChain](https://limechain.tech/)

## SCALE Codec

- [Codec Definition](https://substrate.dev/docs/en/knowledgebase/advanced/codec) - Official
  codec documentation.

### SCALE Codec - Implementations

- [Parity SCALE Codec](https://github.com/paritytech/parity-scale-codec) - Reference implementation
  written in Rust.
- [AssemblyScript](https://github.com/LimeChain/as-scale-codec) - Maintained by LimeChain.
- [TypeScript](https://github.com/polkadot-js/api/tree/master/packages/types) - Maintained by
  Polkadot-JS.
- [Go](https://github.com/itering/scale.go) - Maintained by [Itering](https://www.itering.com/).
- [C++](https://github.com/soramitsu/kagome/tree/master/core/scale) - Maintained by Soramitsu.
- [Haskell](https://github.com/airalab/hs-web3/tree/master/src/Codec) - Maintained by
  [Robonomics Network](https://robonomics.network/).
- [Java](https://github.com/emeraldpay/polkaj/tree/master/polkaj-scale) - Maintained by
  [Emerald](https://emerald.cash/).
- [Ruby](https://github.com/itering/scale.rb) - Maintained by Itering.
- [Python](https://github.com/polkascan/py-scale-codec) - Maintained by Polkascan Foundation.
