# Awesome Bitcoin with stars

A curated list of bitcoin services and tools for software developers
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 497,239 | 🐛 102 | 📅 2026-08-18

## List of content

* [Utilities](#utilities)
* [Blockchain API and Web services](#blockchain-api-and-web-services)
* [Wallets API](#wallets-api)
* [Open Source wallets](#open-source-wallets)
* [Blockchain Explorers](#blockchain-explorers)
* [C Libraries](#c-libraries)
* [C++ Libraries](#c-libraries-1)
* [JavaScript Libraries](#javascript-libraries)
* [PHP Libraries](#php-libraries)
* [Ruby Libraries](#ruby-libraries)
* [Python Libraries](#python-libraries)
* [Java Libraries](#java-libraries)
* [Scala Libraries](#scala-libraries)
* [Swift Libraries](#swift-libraries)
* [.Net Libraries](#net-libraries)
* [Haskell Libraries](#haskell-libraries)
* [Playgrounds](#playgrounds)
* [Blockchain dump](#blockchain-dump)
* [Full nodes](#full-nodes)
* [Read](#read)
* [Course](#course)
* [Additional Resources](#additional-resources)

## Utilities

* [Pycoin](https://github.com/richardkiss/pycoin) ⭐ 1,439 | 🐛 19 | 🌐 Python | 📅 2026-06-18 - Python-based Bitcoin and alt-coin utility library.
* [`<qr-code>`](https://github.com/bitjson/qr-code) ⭐ 1,380 | 🐛 14 | 🌐 TypeScript | 📅 2023-02-28 – A no-framework, no-dependencies, customizable, animate-able, SVG-based `<qr-code>` web component.
* [bx](https://github.com/libbitcoin/libbitcoin-explorer) ⭐ 642 | 🐛 20 | 🌐 C++ | 📅 2024-03-01 - Bitcoin Command Line Tool.
* [Nigiri](https://github.com/vulpemventures/nigiri/) ⭐ 329 | 🐛 45 | 🌐 Go | 📅 2026-07-10 - CLI to quickly fire up a a Bitcoin regtest box along with Electrs and Esplora. Includes faucet and push commands.
* [hellobitcoin](https://github.com/prettymuchbryce/hellobitcoin) ⭐ 254 | 🐛 2 | 🌐 Go | 📅 2017-03-22 - A collection of simple programs which can generate bitcoin wallets, create and sign transactions, and send transactions over the bitcoin network.
* [hal](https://github.com/stevenroose/hal) ⭐ 216 | 🐛 11 | 🌐 Rust | 📅 2026-03-12 - Bitcoin CLI swiss-army-knife (based on rust-bitcoin).
* [PaperVault](https://github.com/boazeb/papervault) ⭐ 62 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-15 - Offline paper-based secret storage using AES-256-GCM and Shamir's Secret Sharing. Create printable encrypted backups of seed phrases with threshold key splitting.
* [txwatcher](https://github.com/tsileo/txwatcher) ⭐ 50 | 🐛 6 | 🌐 Python | 📅 2018-03-04 - A little Python utility that lets you monitor Bitcoin addresses through Blockchain Websocket API and perform custom callbacks.
* [HD Wallet Scanner](https://github.com/alexk111/HD-Wallet-Scanner) ⭐ 35 | 🐛 11 | 🌐 JavaScript | 📅 2022-12-11 - Find all used addresses in your Bitcoin HD wallets bypassing gap limits.
* [BTC Tooling](https://github.com/douvy/btc-tooling) ⭐ 34 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-07 - Bitcoin dashboard with real-time price data, a chart, orderbook, market summary, Twitter/X insights, and halving countdown data. [Live Demo](https://www.btctooling.com/)
* [Lightning Memory](https://github.com/singularityjason/lightning-memory) ⭐ 9 | 🐛 6 | 🌐 Python | 📅 2026-03-25 - Open-source memory layer for AI agents in the Bitcoin/Lightning economy. L402 payment gateway, vendor reputation, spending anomaly detection.
* [Bitcoin Serverless Donations](https://github.com/tombennet/bitcoin-serverless-donations) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-07 - Self-custodial serverless donation widget with address rotation derived from an XPUB.
* [BTC Airgap Bridge](https://github.com/paranoid-qrypto/btc-airgap-bridge) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2025-07-03 - 100% client-side tool for broadcasting signed Bitcoin transactions from air-gapped wallets.
* [SuperScalar MCP](https://github.com/8144225309/superscalar-mcp) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-03 - MCP server for SuperScalar Bitcoin Lightning channel factories — onboard N users in one shared UTXO, no soft fork required.
* [BitKey](https://bitkey.io) - Live USB for airgapped transactions and Bitcoin swiss army knife.
* [Deadhand Protocol](https://deadhandprotocol.com) - Dead man's switch for crypto using Shamir's Secret Sharing to protect seed phrases and ensure inheritance.
* [Mining visualization](https://yogh.io/landing/)
* [Chartscout](https://chartscout.io) - Real-time BTC chart pattern detection and trading alerts across multiple exchanges.
* [Bitcoin Bottom Score](https://bitcoinbottom.app) - Real-time Bitcoin cycle bottom probability tracker. Aggregates 25 on-chain and macro signals (MVRV Z-Score, Puell Multiple, Hash Ribbon, ETF flows) into a daily P(bottom) score. Free, updated twice daily.
* [CryptoCalk](https://cryptocalk.com) - Bitcoin profitability and on-chain calculators: ASIC/GPU mining ROI, hash rate converter, halving countdown, Mayer Multiple, Stock-to-Flow (S2F), Rainbow chart, profit/loss, DCA simulator, tax estimator, liquidation price. Client-side, no signup, available in 6 languages.
* [Freedom Clock](https://freedomclock.io) - Bitcoin-aware FIRE calculator with sell, borrow, and borrow-then-sell spend models. Converts savings and BTC holdings into years of financial freedom. Fully local, no account, MIT. Also an open-source e-ink desk device (\~$30).
* [dont-trust-verify](https://dont-trust-verify.com) - Bitcoin-only client-side tools and self-custody education: 22 calculators, validators and decoders (BIP-39 validator, tx-stuck checker, fee estimator, wallet installer SHA-256 verifier, self-custody score quiz), plus primary-sourced guides and hardware wallet reviews. No signup, no tracking, EN + TH.

## Blockchain API and Web services

* [Esplora](https://github.com/Blockstream/esplora) ⭐ 1,260 | 🐛 189 | 🌐 JavaScript | 📅 2026-08-17 - Self-hosted blockchain explorer.
* [One-Time Address](https://github.com/alexk111/One-Time-Address) ⭐ 82 | 🐛 7 | 🌐 Handlebars | 📅 2022-12-11 A better way to share your Bitcoin address.
* [Chainradar API](https://github.com/yasaricli/chainradar-api) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2018-09-01 - Blockchain Explorer API for Chainradar.
* [3xpl.com](https://3xpl.com/) - Fastest ad-free universal block explorer.
* [Bitquery.io](https://bitquery.io/) - Bitquery provides blockchain data, offering real-time streaming APIs for 40+ chains, NFT APIs, and a money flow investigation tool.
* [block.io](https://block.io)
* [blockchair.com](https://blockchair.com/) - Universal blockchain explorer and search engine.
* [BlockCypher](https://www.blockcypher.com)
* [Insight](https://insight.is)
* [Chain.com](https://chain.com)
* [Coinbase Wallet](https://wallet.coinbase.com/)
* [Cryptocurrency Alerting](https://cryptocurrencyalerting.com/blockchain-alerts.html) - Bitcoin wallet monitoring and blockchain alerts.
* [BTC Connect](https://developers.particle.network/reference/introduction-to-btc-connect) - Unified Bitcoin Layer-1 and Layer-2 wallet connection and account abstraction.
* [Tatum](https://tatum.io/blockchain-api) - The blockchain development platform to build Web3 application. The go-to blockchain data API for Web3 developers.
* [mempool.space](https://mempool.space/docs/api/rest) - Open source and self hostable REST, WebSocket and Electrum RPC API
* [Bitview](https://bitview.space/) - An open source Bitcoin Core data extractor and visualizer (aka FOSS Glassnode)
* [Maestro](https://www.gomaestro.org/) - A high-performance Bitcoin RPC and UTXO indexer API that powers applications with real-time blockchain data, mempool monitoring, and event notifications.
* [OnFinality](https://onfinality.io/en/networks/bitcoin) - Bitcoin RPC endpoints and API access for dApps, wallets, analytics, and backend services.

## Market Data API

* [CoinGapRadar](https://coingapradar.com) - Real-time crypto premium tracker across 9 countries. Monitor kimchi premium and regional price gaps. Free, no signup.
* [CoinMetrics.io](https://docs.coinmetrics.io/) JSON REST API (free as well as paid) with access to market data. Also CSV data file download available.
* [CoinPaprika](https://api.coinpaprika.com) Free crypto market data API. 12,000+ coins, 350+ exchanges, tickers, OHLCV, historical prices. No API key for free tier.
* [Messari.io](https://messari.io/api) JSON REST API (free as well as paid) with access to market data, news, metrics, profile, etc.
* [PreReason](https://www.prereason.com) - Pre-analyzed Bitcoin market briefings via REST API. Covers BTC price, hash rate, difficulty, mining production costs, treasury holdings (30 public companies), and macro signals that move Bitcoin (Fed balance sheet, M2, Treasury yields). Returns trend direction, confidence scores, and regime classification instead of raw numbers. Free tier available.

## Wallets API

* [BitGo](https://developers.bitgo.com)
* [Coinbase](https://developers.coinbase.com)
* [Blockchain.com](https://www.blockchain.com/api)
* [BIP32](http://bip32.org)
* [walletOS](https://www.pinestreetlabs.com/walletos/)

## Open Source Wallets

* [Blue Wallet](https://bluewallet.io/)
* [CoPay by BitPay](https://copay.io/)
* [Coinb.in](https://coinb.in)
* [Coin Wallet](https://coin.space/)
* [Electrum](https://electrum.org/)
* [Green](https://blockstream.com/green/)
* [Sparrow](https://sparrowwallet.com/)
* [Wasabi Wallet](https://wasabiwallet.io/)

## Privacy projects

* [Joinmarket](https://github.com/JoinMarket-Org/joinmarket-clientserver) ⚠️ Archived - Decentralized CoinJoin implementation
* [Jam](https://jamapp.org/) - User friendly frontend for Joinmarket

## Blockchain Explorers

* [3xpl.com](https://3xpl.com/bitcoin) - Fastest ad-free universal block explorer.
* [Chain.so](http://chain.so)
* [Blockchain.com](https://blockchain.com)
* [Blockchair.com](https://blockchair.com/bitcoin) - Universal blockchain explorer and search engine.
* [Blockstream.info](https://blockstream.info) - Blockchain explorer with API (mainnet, testnet and Liquid).
* [Bitcoin Transaction Explorer](https://github.com/JornC/bitcoin-transaction-explorer) ⭐ 184 | 🐛 15 | 🌐 Java | 📅 2026-01-16
* [Blockexplorer.com](https://blockexplorer.com)
* [Smartbit](https://www.smartbit.com.au)
* [mempool.space](https://mempool.space/) - Open source, self hostable blockchain, mempool and lightning network explorer

## C Libraries

* [libsecp256k1](https://github.com/bitcoin-core/secp256k1) ⭐ 2,473 | 🐛 153 | 🌐 C | 📅 2026-08-17
* [UltrafastSecp256k1](https://github.com/shrec/UltrafastSecp256k1) ⭐ 51 | 🐛 4 | 🌐 C++ | 📅 2026-08-17 - High-performance `secp256k1` engine with a stable C ABI, CPU, CUDA, OpenCL, embedded, and WebAssembly targets.

## C++ Libraries

* [Libbitcoin](https://libbitcoin.org/)
* [Libbitcoin](https://libbitcoin.info/) - A set of cross platform C++ libraries for building bitcoin applications
* [libwally-core](https://github.com/ElementsProject/libwally-core) ⭐ 306 | 🐛 32 | 🌐 C | 📅 2026-08-10

## JavaScript Libraries

* [Bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib) ⭐ 5,998 | 🐛 52 | 🌐 JavaScript | 📅 2026-02-17
* [Bitcore Library](https://github.com/bitpay/bitcore/tree/v8.0.0/packages/bitcore-lib) ⭐ 4,989 | 🐛 47 | 🌐 TypeScript | 📅 2026-08-06
* [bcoin](https://github.com/bcoin-org/bcoin) ⭐ 3,067 | 🐛 201 | 🌐 JavaScript | 📅 2024-02-12 - Javascript bitcoin library for node.js and browsers.
* [noble-curves](https://github.com/paulmillr/noble-curves) ⭐ 937 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-17 — audited implementation of secp256k1 + schnorr in pure typescript
* [noble-secp256k1](https://github.com/paulmillr/noble-secp256k1) ⭐ 882 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-16 — alternative implementation of secp256k1: size is only 4KB gzipped; lots of comments, very valuable for learning how algorithms work
* [scure-btc-signer](https://github.com/paulmillr/scure-btc-signer) ⭐ 238 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-17 — audited & minimal library for creating, signing & decoding Bitcoin transactions. With Schnorr, Taproot, UTXO & PSBT.
* [Awesome CryptoCoinJS](https://github.com/cryptocoinjs/awesome-cryptocoinjs) ⭐ 61 | 🐛 0 | 📅 2016-02-17
* [BlockTrail SDK NodeJS](https://github.com/blocktrail/blocktrail-sdk-nodejs) ⭐ 39 | 🐛 19 | 🌐 JavaScript | 📅 2022-03-09
* [bitcoin-sdk-js](https://github.com/ChrisCho-H/bitcoin-sdk-js) ⭐ 39 | 🐛 1 | 🌐 JavaScript | 📅 2025-10-24 — Bitcoin TypeScript/JavaScript Library for NodeJS, Browser and Mobile. Segwit & Taproot support.
* [toll-booth](https://github.com/forgesworn/toll-booth) ⭐ 2 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-17 - HTTP 402 payment middleware for Node.js; gates any API behind Lightning, Cashu, or stablecoin payments with five backend options.
* [Cryptocoin](http://cryptocoinjs.com/#modules)
* [Libauth](https://libauth.org/) – A lightweight, zero-dependency, JavaScript/TypeScript bitcoin library.

## PHP Libraries

* [PHP-OP\_RETURN](https://github.com/coinspark/php-OP_RETURN) ⭐ 83 | 🐛 7 | 🌐 PHP | 📅 2020-03-09
* [BlockTrail PHP SDK](https://github.com/blocktrail/blocktrail-sdk-php) ⭐ 48 | 🐛 37 | 🌐 PHP | 📅 2024-04-28

## Ruby Libraries

* [Bitcoin-ruby](https://github.com/lian/bitcoin-ruby) ⭐ 920 | 🐛 39 | 🌐 Ruby | 📅 2024-08-19
* [bitcoinrb](https://github.com/chaintope/bitcoinrb) ⭐ 67 | 🐛 1 | 🌐 Ruby | 📅 2026-08-15 - Ruby bitcoin library including script interpreter.
* [bech32rb](https://github.com/azuchi/bech32rb) ⭐ 22 | 🐛 1 | 🌐 Ruby | 📅 2026-08-07 - Bech32 and Bech32m encode/decode library.
* [bip-schnorrrb](https://github.com/chaintope/bip-schnorrrb) ⭐ 8 | 🐛 0 | 🌐 Ruby | 📅 2026-08-07 - Schnorr signature library for Bitcoin.

## Rust Libraries

* [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) ⭐ 2,655 | 🐛 483 | 🌐 Rust | 📅 2026-08-18 - support for de/serialization, parsing and executing on data-structures and network messages.
* [Bithoven](https://github.com/ChrisCho-H/bithoven) ⭐ 43 | 🐛 5 | 🌐 Rust | 📅 2026-02-25 -  A High-Level, Imperative Language for Bitcoin Smart Contracts, featuring an LR(1) parser with static analysis for compile-time safety.
* [Bitcoin Dev Kit (BDK)](https://bitcoindevkit.org/) - With BDK, you can seamlessly build cross platform mobile wallets
* [Lightning Dev Kit (LDK)](https://lightningdevkit.org/) -  Complete Lightning implementation packaged as an SDK

## Python Libraries

* [pycoin](https://github.com/richardkiss/pycoin) ⭐ 1,439 | 🐛 19 | 🌐 Python | 📅 2026-06-18 - Python library for Bitcoin keys, signatures, transactions. Includes full VM implementation and tools for manipulating keys (ku) and transactions (tx).
* [pybitcointools](https://github.com/vbuterin/pybitcointools) ⭐ 1,333 | 🐛 89 | 📅 2024-07-03 - Python library for Bitcoin signatures and transactions from Vitalik Buterin. Project discontinued.
* [bitcoin\_tools](https://github.com/sr-gi/bitcoin_tools) ⭐ 312 | 🐛 7 | 🌐 Python | 📅 2022-01-30 - Python library for building and analyzing transactions and scripts (both standard and custom). Comes along with a UTXO set analysis tool. Includes several examples and exhaustive documentation.
* [BlockTrail SDK Python](https://github.com/blocktrail/blocktrail-sdk-python) ⭐ 23 | 🐛 7 | 🌐 Python | 📅 2018-02-27
* [pybtc](https://github.com/mohanson/pybtc) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-07-09 - Python BTC is an experimental project that aims to provide human-friendly interfaces for common BTC operations.
* [btctxstore](https://github.com/F483/btctxstore) ⭐ 11 | 🐛 16 | 🌐 Python | 📅 2024-08-02 - Simple library to store/retrieve information in bitcoin transactions using OP\_RETURN.

## Java Libraries

> Note that you can also use [Scala libraries](#scala-libraries) in Java.

* [XChange](https://github.com/knowm/XChange) ⭐ 4,079 | 🐛 194 | 🌐 Java | 📅 2026-07-31 - Library that provides a simple and consistent API for interacting with 50+ Bitcoin currency exchanges.
* [Bitcoin Spring Boot Starter](https://github.com/theborakompanioni/bitcoin-spring-boot-starter) ⭐ 85 | 🐛 15 | 🌐 Java | 📅 2026-08-16 - Bitcoin integration for Spring Boot applications.
* [bech32](https://github.com/NostrGameEngine/bech32) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-06-07 - Bech32 and Bech32m encode/decode library.
* [BitcoinJ](https://bitcoinj.github.io)

## Scala libraries

> Note that you can also use [Java libraries](#java-libraries) in Scala.

* [Bitcoin-S](https://bitcoin-s.org) - Scala/JVM toolkit for Bitcoin applications, includes Bitcoin data structures, transaction signing, strongly typed `bitcoind`/Eclair RPC clients, and more.

## Swift libraries

* [secp256k1.swift](https://github.com/GigaBitcoin/secp256k1.swift) ⭐ 156 | 🐛 3 | 🌐 Swift | 📅 2026-08-10 - Swift package for secp256k1 applications, includes Elliptic Curve operations, Schnorr, ZKP and more for Bitcoin.

## .Net Libraries

* [NBitcoin](https://github.com/MetacoSA/NBitcoin) ⭐ 1,942 | 🐛 116 | 🌐 C# | 📅 2026-08-12 - Comprehensive Bitcoin library for the .NET framework.
* [BitcoinLib](https://github.com/cryptean/bitcoinlib) ⭐ 413 | 🐛 11 | 🌐 C# | 📅 2022-12-08 - The most complete, up-to-date, battle-tested .net Library and RPC Wrapper for Bitcoin and Altcoins in C#.

## Haskell Libraries

* [Haskoin-core](https://github.com/haskoin/haskoin-core) ⭐ 534 | 🐛 1 | 🌐 Haskell | 📅 2026-08-12 - Haskoin Core is a library of Bitcoin and Bitcoin Cash functions written in Haskell.

## Playgrounds

* [blockchain-demo](https://github.com/anders94/blockchain-demo/) ⭐ 5,657 | 🐛 11 | 🌐 Pug | 📅 2026-07-29 - A web-based demonstration of blockchain concepts.
* [Bitcoin IDE](https://github.com/siminchen/bitcoinIDE) ⭐ 222 | 🐛 16 | 🌐 JavaScript | 📅 2019-10-30 - Bitcoin Script for dummies.
* [Bitcoin Script Debugger](https://github.com/liuhongchao/bitcoin4s) ⭐ 60 | 🐛 4 | 🌐 Scala | 📅 2026-07-26 - Visualize Bitcoin script execution for real transactions.
* [Script Debugger](https://github.com/kallewoof/btcdeb) ⭐ 45 | 🐛 0 | 🌐 C | 📅 2026-07-26
* [Script Playground](https://www.crmarsh.com/script-playground/)
* [Bitcore Playground](https://bitcore.io/playground/)
* [Mnemonic Code generator](https://iancoleman.io/bip39/)
* [Bitauth IDE](https://ide.bitauth.com/) – An interactive development environment for Bitcoin contracts.
* [ChainQuery Bitcoin RPC](https://chainquery.com) - Run select bitcoin RPC API calls and read full RPC docs in your browser.
* [Bithoven IDE](https://bithoven-lang.github.io/bithoven/ide/) -  Web IDE for Bithoven, A High-Level, Imperative Language for Bitcoin Smart Contracts.

## Blockchain dump

* [BitcoinABE](https://github.com/bitcoin-abe/bitcoin-abe) ⭐ 979 | 🐛 159 | 🌐 Python | 📅 2023-06-26 - Abe: block browser for Bitcoin and similar currencies.
* [BitcoinDatabaseGenerator](https://github.com/ladimolnar/BitcoinDatabaseGenerator) ⭐ 127 | 🐛 8 | 🌐 C# | 📅 2017-04-30 - A high performance data transfer tool that can be used to copy data from Bitcoin Core blockchain files to a SQL Server database.
* [Blockparser+SQL](https://github.com/mcdee/blockparser) ⭐ 60 | 🐛 0 | 🌐 C++ | 📅 2021-10-05 - Fast, quick and dirty bitcoin blockchain parser.
* [Chaingraph](https://github.com/bitauth/chaingraph/) ⭐ 60 | 🐛 67 | 🌐 TypeScript | 📅 2025-11-16 – A multi-node blockchain indexer and GraphQL API.

## Full nodes

* [btcd](https://github.com/btcsuite/btcd/) ⭐ 6,698 | 🐛 342 | 🌐 Go | 📅 2026-08-12 - Go-based full node since 2013.
* [Bitcore](https://github.com/bitpay/bitcore) ⭐ 4,989 | 🐛 47 | 🌐 TypeScript | 📅 2026-08-06 - Formerly just a Nodejs library, now a full node.
* [Bitcore Node](https://github.com/bitpay/bitcore-node) ⭐ 352 | 🐛 89 | 🌐 JavaScript | 📅 2023-03-08 - bitcoind linked to node.js by BitPay.
* [Fullnode](https://github.com/moneybutton/yours-bitcoin) ⭐ 193 | 🐛 29 | 🌐 JavaScript | 📅 2022-04-16 - Javascript implementation of bitcoin.
* [Bitcoin-ruby-node](https://github.com/mhanne/bitcoin-ruby-node) ⭐ 26 | 🐛 3 | 🌐 Ruby | 📅 2016-04-23 - bitcoin node based on bitcoin-ruby-blockchain.
* [Bitcoin Core](https://bitcoincore.org/) - direct descendant of the original Bitcoin implementation in C++

## Read

* [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook) ⭐ 25,290 | 🐛 191 | 🌐 HTML | 📅 2024-12-26
* [Bitcoin Protocol Development Curriculum - Chaincode Labs](https://github.com/chaincodelabs/bitcoin-curriculum) ⭐ 696 | 🐛 0 | 📅 2025-08-23.
* [Lightning Network Protocol Development Curriculum - Chaincode Labs](https://github.com/chaincodelabs/lightning-curriculum) ⭐ 371 | 🐛 0 | 📅 2023-12-07.
* [Bitcoin Programming with BitcoinJS and Bitcoin Core CLI](https://github.com/bitcoin-studio/Bitcoin-Programming-with-BitcoinJS) ⭐ 163 | 🐛 5 | 🌐 CSS | 📅 2023-01-10.
* [A Gentle Introduction to Bitcoin Core Development](https://medium.com/bitcoin-tech-talk/a-gentle-introduction-to-bitcoin-core-development-fdc95eaee6b8)
* [Grokking Bitcoin](https://www.manning.com/books/grokking-bitcoin) - An in-depth technical book with rich illustrations.
* [Bitcoin Stackexchange](https://bitcoin.stackexchange.com)
* [Elliptic Curve Cryptography A Gentle Introduction](https://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/).
* [btcinformation.org / Developer Documentation](https://btcinformation.org/en/developer-documentation) - Find useful resources, guides and reference material for developers.

## Course

* [Bitcoin & Cryptocurrency](http://bitcoinbook.cs.princeton.edu/).

## Additional Resources

* [@lopp / Bitcoin Developers](https://twitter.com/lopp/lists/bitcoin-developers) - Software developers who have experience working on Bitcoin implementations or applications.
* [@lopp / Lightning Developers](https://twitter.com/i/lists/981976067551490048) - Software developers with experience working on LN implementations / applications.
* [Practical Bitcoin Info - Google Sheets](https://docs.google.com/spreadsheets/d/1Z3Ofa4P8097VWV70Z_bMqIMladngvm-Ck24ot9TDNmw/).
* [A brief history of Bitcoin development...](https://www.youtube.com/watch?v=ZfFNce6CVsE)
* [bitcoin-resources.com](https://bitcoin-resources.com/) Meta-list of Bitcoin resources, from books, articles, to podcasts.
* [Jameson Lopp Bitcoin Resource List](https://www.lopp.net/bitcoin-information.html) Very detailed curated Bitcoin resource list and meta-list by J. Lopp
* [Svrgnty.com: Everything Bitcoin](https://svrgnty.com/) A curated list of the best Bitcoin resources.
* [River Learn](https://river.com/learn) A collection of educational resources to learn about Bitcoin basics, investing, technology, and more.
* [BitcoinCompanies](https://bitcoincompanies.co/) - Corporate Bitcoin treasury map and leaderboard with claimed vs verified holdings.
* [Learn me a Bitcoin - Greg Walker](https://learnmeabitcoin.com/) - extensive learning resource for bitcoin developers
* [Bennet.org](https://bennet.org/) - Interactive technical guides for bitcoiners.
* [Knowing Bitcoin](https://knowingbitcoin.com/) - Comprehensive Bitcoin education with 214+ in-depth guides on Lightning Network, wallets, security, privacy, and nodes.
* [Bitcoin.diy](https://bitcoin.diy) - Bitcoin-only education and hardware wallet reviews, focused on self-custody for beginners and intermediate users.
* [Bitcoin Institute](https://bitcoin-institute.pages.dev) - Bilingual (EN/JP) archive of Satoshi Nakamoto primary sources: forum posts, emails, and mailing-list messages, each linked to its original source.

***

Inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 497,239 | 🐛 102 | 📅 2026-08-18 list thing.
Created by BlockchainU fellows.

***

### License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Igor Barinov](https://github.com/igorbarinov/) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
