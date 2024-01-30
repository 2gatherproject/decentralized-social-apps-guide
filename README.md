## Awesome Decentralized, Open-Source Social Networking and Collaboration Applications and Platforms

### Contents
* [Purpose](#purpose)
* [Applications and Platforms](#applications-and-platforms)
    * [Social Networking](#social-networking)
    * [Collaboration](#collaboration)
    * [Identity and Authorization](#identity-and-authorization)
    * [Decentralized Protocols](#decentralized-protocols)
    * [Decentralized Networking](#decentralized-networking)
    * [Decentralized Databases](#decentralized-databases)
    * [Decentralized Search and Indexing](#decentralized-search-and-indexing)
    * [Decentralized AI](#decentralized-ai)
    * [Decentralized Publishing](#decentralized-publishing)
* [Common Issues](#common-issues)
* [Concepts](#concepts)
* [Related Awesome Lists](#related-awesome-lists)
* [Initiatives and Institutions](#initiatives-and-institutions)
* [Roadmap](#roadmap)
* [Contributions](#contributions)
* [License](#license)

### Purpose
The purpose of this document is to provide an overview and guide to existing open-source decentralized applications (dapps) and platforms for social interaction, social networking, social media, social engagement and creative or project-based collaboration (e.g. Decentralized Autonomous Organizations).

For our purposes, **decentralized** means that these apps are peer-to-peer (P2P) and/or rely on decentralized infrastructure like public, open-source blockchains (e.g. Ethereum or Bitcoin) or protocols (e.g. IPFS, Secure Scuttlebut, Dat, Gun, WebTorrent, ActivityPub). If they rely on blockchains or protocols like these, it must be practically possible for users to run their own nodes without having to pay fees to any centralized entity.

_Decentralized_ apps and platforms are distinguished from _centralized_ ones (e.g. Facebook) that rely on centrally managed servers/databases and _federated_ ones that rely on a network of locally centralized servers (e.g. Mastodon).

Only _open-source_ apps and platforms will be listed here.

This is a curated list. More developed apps and platforms with more features and/or a wider user base may be highlighted, but all apps/platforms that meet the overall purpose will be listed here if submitted.


### Applications and Platforms

#### Social Networking

##### Applications

* [Acorn](https://github.com/lightningrodlabs/acorn) - Acorn is an open-source, peer-to-peer project management application, built with Holochain.
* [Aether](https://getaether.net/) - Open source, self-governing communities with auditable moderation and mod elections
* [Bluesky](https://github.com/bluesky-social/social-app) - An app and project originally spun out of Twitter, which is building the AT Protocol (see below), a new foundation for public conversation and social networking which gives creators independence from platforms, developers the freedom to build, and users a choice in their experience.
* [Briar](https://briarproject.org/) - WhatsApp clone with security focus. GPL licensed
* [Circles](https://github.com/KombuchaPrivacy/circles-ios) - A social media app (iOS only) based off of the Matrix platform (see more below), currently in beta.
* [Effectio](https://github.com/effektio/effektio) Community Communication and casual social organising platform, built on top of Matrix protocol.
* [Element](https://element.io/), formerly known as Riot IM, is the reference messaging client for the Matrix platform. Matrix is currently federated but a fully decentralized version is under active development (see below). Strongly private group messaging using MegOlm double-ratchet. Backed by [Automattic](https://matrix.org/blog/2020/05/21/welcoming-automattic-to-matrix), the creators of Wordpress, among others. Used by the [French](https://matrix.org/blog/2018/04/26/matrix-and-riot-confirmed-as-the-basis-for-frances-secure-instant-messenger-app) and [German](https://www.heise.de/newsticker/meldung/Bundeswehr-setzt-kuenftig-auf-Matrix-als-Messenger-4719474.html) governments and other clients. Apache 2.0 licensed
* [DTube](https://d.tube/) - Youtube clone using Steemit blockchain and IPFS. GPL licensed
* [Group Income](https://github.com/okTurtles/group-income) - Voluntary Basic Income system that's decentralized and end-to-end encrypted. Uses Shelter Protocol (see below).
* [Iris](https://irislib.github.io/) - Social sharing using Gun and IPFS
* [Jami](https://jami.net/) - WhatsApp clone
* [Junto](https://junto.foundation/) - Social network on Holochain
* [Lemmy](https://github.com/LemmyNet/lemmy) - An alternative to Reddit. Curently only federated, but because it is in Rust it could be ported to WASM and made fully decentralized, like Matrix (see below)
* [Matrix Social](https://codeberg.org/imbev/matrix-social) A Matrix "Social Media" client
* [MinesTrix](https://gitlab.com/minestrix/minestrix-flutter) - A social media app (Flutter: Android, iOS and web) based off of the Matrix platform (see more below), still in alpha.
* [Minttner](https://github.com/MintterHypermedia/mintter) - An app for knowledge communities. Powered by the Hypermedia protocol.
* [NOSTR Clients (multiple)](https://github.com/aljazceru/awesome-nostr#clients) NOSTR is an open protocol for censorship-resistant global networks, and this lists multiple clients that support it
* [Open Super Dapp](https://github.com/2gatherproject/open-super-dapp-android) - Your gateway to the new digital commons. A "super app" with integrated mobile messenger, Ethereum wallet, and Web 3.0 browser built on open, decentralized, and encrypted protocols. Pre alpha. Seeking developers/supporters.
* [Open Wallet Foundation](https://github.com/openwallet-foundation) - The mission of the OWF is to develop an open source engine to enable secure and interoperable multi-purpose wallets anyone can use to build solutions.
* [Peerpeth](https://peepeth.com/welcome) - Twitter clone on the Ethereum blockchain
* [PeerTube](https://joinpeertube.org/en/) - Youtube clone using ActivityPub
* [Patchwork](https://github.com/ssbc/patchwork) - Social network on Secure Scuttlebut. AGPL licensed
* [Ricochet Refresh](https://github.com/blueprint-freespeech/ricochet-refresh/tree/main) - Ricochet Refresh is the new updated version of [Ricochet](https://github.com/ricochet-im/ricochet), supported by Blueprint for Free Speech. Ricochet is anonymous, metadata-resistant instant messaging
* [Quiet](https://github.com/TryQuiet/quiet) - A private, p2p alternative to Slack and Discord built on Tor & IPFS
* [Textile Photos](https://github.com/textileio/photos) - A photo sharing app using Textile (See below)
* [Veilid Chat](https://veilid.com/chat/) - VeilidChat is a demo of the Veilid framework and protocol working.
* [Vocdoni](https://blog.vocdoni.io/vocdoni-technical-overview-v1/) - A voting and collaboration platform, affiliated with Aragon, on an Ethereum compatible sidechain


##### Platforms

* [3box](https://3box.io/) Nascent social networking platform using Ethereum and OrbitDB (IPFS-based)
* [DSNP](https://www.dsnp.org/) Decentralized Social Network Protocol - a public social graph completely disconnected from financial incentives from [Amplica Labs](https://amplica.io/) and [Project Liberty](https://projectliberty.io/), built on [Frequency](https://www.frequency.xyz/) and [Polkadot](https://polkadot.network/)
* [Holepunch](https://docs.holepunch.to/) - Holepunch equips developers with a powerful suite of independent components to effortlessly construct peer-to-peer applications. Includes information on Hypercore, Hyperbee, Hyperdrive, Autobase, HyperDHT, and Hyperswarm open source projects.
* [Mix platform](https://www.mix-blockchain.org/) - Using Ethereum and IPFS
* [Matrix platform](https://matrix.org/) - Matrix is an extendable social messaging platform that is currently federated/distributed, but they are looking into a [fully decentralized P2P version](https://fosdem.org/2020/schedule/event/dip_p2p_matrix/) with an innovative approach that puts the federated server onto people's devices! Something to watch - A [discussion room](https://matrix.to/#/#p2p:matrix.org) is available to follow developments. Strongly private group messaging using MegOlm double-ratchet. Supports [bridges](https://matrix.org/bridges/) to existing "walled garden" corporate networks and custom [bots](https://matrix.org/bots/). Matrix is governed through an transparent, participatory process overseen by the [Matrix Foundation](https://matrix.org/foundation/). Element is Matrix's reference client (see above).
* [OddSDK](https://github.com/oddsdk) - ODD SDK is Fission's true local-first, edge computing stack. ODD SDK empowers you to build fully distributed web applications with auth and storage without needing a complex backend
* [Sia](https://github.com/SiaFoundation/siad) - A decentralized cloud storage platform.
* [Spritely](https://spritelyproject.org/) - An alpha ecosystem of protocols and projects leveraging ActivityPub and Object Capabilities. Read about [The Heart of Spritely: Distributed Objects and Capability Security](https://spritely.institute/static/papers/spritely-core.html) here.
* [SecuShare](https://secushare.org/) - decentralized messaging on GNU:Net (see below)
* [Textile platform](https://textile.io/) - Using IPFS


##### Meta

* [app.co](https://app.co/) - Decentralized app store (not all are open source!)
* An overview of existing social networking options including decentralized ones (6/26/19): [So You Want to Leave Facebook](https://hackernoon.com/so-you-want-to-leave-facebook-1ab3603f164a)

#### Collaboration


##### Ethereum blockchain based

###### Apps

* [Alchemy](https://daostack.io/alchemy) Proposal voting/funding app built on DAOStack
* [Gitcoin](https://gitcoin.co/) - Bounties for software projects

###### DAO platforms
* [Aragon platform](https://aragon.one/) - Now affiliated with Vocdoni
* [DAOStack platform](https://daostack.io/)
* [Colony platform](https://colony.io/)
* [Moloch platform](https://github.com/MolochVentures/moloch)

###### Ethereum, other

* [BroncoVotes](https://github.com/pmarella2/BroncoVotes) - Ethereum based secure voting platform
* [Nouns Anonymous Voting](https://github.com/aragonzkresearch/nouns-anonymous-voting) - A proof of concept implementation of anonymous voting on Ethereum, leveraging [Timelock](https://www.timelock.zone/) ([on Github](https://github.com/aragonzkresearch/tlcs-rust)), a public platform that allows companies and individuals to encrypt data for future decryption, which in turn relies on [dRand](https://drand.love/) ([on Github](https://github.com/drand/drand)), a trusted distributed beacon of public randomness, from the [League of Entropy](https://blog.cloudflare.com/league-of-entropy/).
* [PeepsDemocracy](https://www.peepsdemocracy.com/) - ActBlue alternative. Nothing there yet? Open source?


##### Bitcoin blockchain based

* [Blockstack platform](https://blockstack.org/) - [Various dapps](https://blockstack.org/try-blockstack) are available, including [Graphite](https://www.graphitedocs.com/), a Google Docs/Sheets clone. Some but not all are open source

##### Github/Gitlab alternatives

* [git-bug](https://github.com/MichaelMure/git-bug.git) Decentralized issue tracking using git itself
* [git-remote-ipfs](https://github.com/cryptix/git-remote-ipfs/) - Git push/pull to IPFS
* [git-ssb](https://github.com/noffle/git-ssb-intro) - Git over Secure Scuttlebut
* [Mango](https://github.com/axic/mango) - Git using Ethereum, IPFS
* [Radicle](http://www.radicle.xyz/) - using IPFS

##### Other

* [Secret voting (Enigma)](https://blog.enigma.co/secret-voting-smart-contracts-with-enigma-a-walkthrough-5bb976164753) using Enigma (see below)
* [Secret voting (Oasis)](https://docs.oasiscloud.io/en/latest/secret-ballot/) - using Oasis (see below)
* [Secret voting (Vocdoni)](https://blog.vocdoni.io/vocdoni-technical-overview-v1/) - using zk-SNARKs
* [Trellis](https://github.com/automerge/trellis) - Trello clone based on MPL (Automerge & WebRTC)

##### Meta
* An overview of existing Ethereum-based DAO (decentralized autonomous organization) platforms (6/16/19): [Aragon, DAOStack, Colony, Moloch](https://kronosapiens.github.io/blog/2019/06/16/aragon-daostack-colony-moloch.html)

#### Identity and Authorization

Identity services are a key requirement of most social/collaborative apps. Decentralized and self-sovereign identity platforms and "wallets" are listed here.

* [Biscuit Authorization](https://github.com/biscuit-auth/biscuit) - Biscuit is a revocable authorization token with decentralized verification, offline attenuation and strong security policy enforcement based on a logic language. How to [integrate with OAuth and OIDC](https://www.biscuitsec.org/blog/oauth-oidc/).
* [Ceramic](https://www.ceramic.network/) DIDs and linked documents on IPFS. Affiliated with 3Box and Ethereum ecosystem. (Not affiliated with Decentralized Identity Foundation?)
* [DBSC](https://github.com/WICG/dbsc) - Device Bound Session Credentials. Not strictly for decentralized uses, but may be helpful. Device Bound Session Credentials (DBSC) aims to reduce account hijacking caused by cookie theft. It does so by introducing a protocol and browser infrastructure to maintain and prove possession of a cryptographic key.
* [DID-SIOP](https://identity.foundation/did-siop/) - OpenID protocol for self-issued (self-sovereign) identities, e.g. using a public/private key or cryptography wallet
* [Ethereum Attestation Service](https://github.com/ethereum-attestation-service/eas-contracts) - A free and open protocol for on-chain attestations on EVM compatible blockchains
* [IDM](https://github.com/ipfs-shipyard/pm-idm) General purpose identity manager for DIDs
* [iden3](https://iden3.io/) Ethereum identity platform leveraging zk-SNARKs (See below)
* [ION](https://github.com/decentralized-identity/ion) DID Method implementation using the Sidetree protocol on top of Bitcoin. From [Decentralized Identity Foundation](https://identity.foundation/).
* [ipid](https://github.com/jonnycrunch/ipid) - DIDs using IPFS
* [Hyperledger Indy](https://www.hyperledger.org/projects/hyperledger-indy)
* [Keycard](https://keycard.tech/) - A new type of smartcard and open source API for simple integration with crypto wallets, DApps, and hardware
* [MetaMask](https://metamask.io/) Ethereum wallet/identity manager
* [OpenPubkey](https://www.bastionzero.com/blog/bastionzeros-openpubkey-why-i-think-it-is-the-most-important-security-research-ive-done) - OpenPubkey adds user generated cryptographic signatures to OpenID Connect. See also [journal article](https://eprint.iacr.org/2023/296.pdf) on the protocol. They say open source code is available, but where?
* [OpenABE](https://github.com/zeutro/openabe) - Open source cryptographic library with attribute-based encryption implementations in C/C++
* [Rabe](https://github.com/Fraunhofer-AISEC/rabe) - Rabe is an Attribute Based Encryption library, written in Rust
* [Reclaim:ID](https://reclaimid.gitlab.io/) - Decentralized identity on GNU:net with OpenID interface
* [Status.im](https://status.im/) - Status is a secure messaging app, crypto wallet, and Web3 browser
* [Trezor](https://trezor.io/) Open-source hardware wallet/identity manager
* [uPort](https://www.uport.me/) Ethereum wallet/identity manager
* [Wallet Connect](https://walletconnect.org/) - Open protocol for connecting Wallets to Dapps
* [zkEmail](https://github.com/zkemail) - Proof of Email, using Circom & Ethereum. Email a relayer in order to transfer money or transact on Ethereum, anonymously. Peer to peer marketplace for decentralized on ramp/offramp to ethereum via Venmo and other payment services.
* [zkLocus](https://github.com/iluxonchik/zkLocus) - zkLocus enables users to authenticate their geographical location with service providers while preserving their privacy. Runs on Mina Protocol (see below).

##### Meta
* [Decentralized Identity Foundation](https://identity.foundation/)
* [Decentralized Web Developer Survey 2020](https://medium.com/fluence-network/decentralized-web-developer-report-2020-5b41a8d86789)

#### Decentralized Protocols
These are the underlying decentralized protocols powering the dapps and platforms above

* [ActivityPub](https://activitypub.rocks/)
* [AT Protocol](https://github.com/bluesky-social/atproto) - The Authenticated Transfer Protocol is the new decentralized protocol developed by Bluesky (a project spun out of Twitter), and is a federated protocol for large-scale distributed social applications.
* [Automerge](https://github.com/automerge/automerge) - CRDT implementation
* [Bitcoin blockchain](https://bitcoin.org/en/)
* [BitTorrent](https://en.wikipedia.org/wiki/BitTorrent)
* [CACAO](https://github.com/ceramicnetwork/cacao) - Chain-agnostic Object Capabilities (OCAP), created using EIP-4361 (or similar for other blockchains), as an [IPLD](https://github.com/ipld/ipld) object. Can work on content addressable storage like IPFS.
* [Circom](https://github.com/iden3/circom) - a novel domain-specific language for defining arithmetic circuits that can be used to generate zero-knowledge proof, with available compiler.
* [Dat](https://www.datprotocol.com/) - A mutable, identity addressed file/data sharing protocol
* [DIDComm](https://github.com/decentralized-identity/didcomm-messaging) - The purpose of DIDComm Messaging is to provide a secure, private communication methodology built atop the decentralized design of DIDs (see below). Intended to work over any transport. Here is an official working [demo](https://github.com/decentralized-identity/didcomm-demo).
* [Enigma](https://enigma.co/) - Secure "secret contract" protocol extended from Ethereum. Founders of [Secret Network](https://scrt.network/)
* [Ethereum blockchain](https://www.ethereum.org/)
* [Farcaster](https://github.com/farcasterxyz/protocol) - Farcaster is a community-created protocol for building decentralized social applications. Developers can use Farcaster to build new, decentralized social networks, letting the protocol deal with the hard problems of managing user identities and data. Users can create a new account that they control and sign up to use any of these applications. Users are always in control of their data and identity and can switch freely between applications.
* [Fluid Framework](https://fluidframework.com/docs/) - for managing state for collaborative decentralized apps. Requires servers for operation.
* [Gun](https://github.com/amark/gun) - P2P CRDT protocol implementation
* [Holochain](https://holochain.org/)
* [Hyperswarm](https://github.com/hyperswarm/hyperswarm) - A distributed networking stack for connecting peers.
* [Iroh](https://github.com/n0-computer/iroh) - Iroh is a protocol for syncing & moving bytes. Bytes of any size, on any device. At its core, it's a peer-2-peer network built on a magic socket that establishes QUIC connections between peers. Peers request and provide blobs of opaque bytes that are incrementally verified by their BLAKE3 hash during transfer. Emerged as a [fork/adaptation of IPFS](https://iroh.computer/docs/ipfs). [Example usage](https://iroh.computer/sendme) to send P2P files.
* [Lens Protocol](https://www.lens.xyz/) - Lens Protocol is a composable and decentralized social graph, ready for you to build on so you can focus on creating a great experience, not scaling your users. Built on Polygon/Ethereum chains.
* [Loro](https://github.com/loro-dev/loro) - Reimagine state management with CRDTs. Easily enable collaboration and time-travel on your app.
* [IPFS](https://ipfs.io/) - An immutable, content addressed file/data sharing protocol. libp2p based
* [Mina Protocol](https://github.com/MinaProtocol/mina) - Mina is a new cryptocurrency with a constant size blockchain, improving scaling while maintaining decentralization and security (Javascript/Browser)
* [MPL](https://github.com/automerge/mpl) - Using Automerge and WebRTC
* [Noir](https://github.com/noir-lang/awesome-noir) - Noir is a Domain Specific Language for SNARK proving systems. It has been designed to use any ACIR compatible proving system. [NoirJS](https://noir-lang.org/noir_js/) is a TypeScript library that make it easy to use Noir on your dapp, webapp, Node.js server, website, etc. Can work with any proving system, but works out of the box with [Barretenberg](https://github.com/AztecProtocol/barretenberg) proving backend.
* [NOSTR](https://github.com/nostr-protocol/nostr) NOSTR stands for "Notes and Other Stuff Transmitted by Relays" and is an open protocol for censorship-resistant global networks. [Awesome NOSTR]( https://github.com/aljazceru/awesome-nostr)
* [Oasis](https://www.oasislabs.com/) - Secure "secret contract" protocol extended from Ethereum
* [Secure Scuttlebut](https://www.scuttlebutt.nz/)
* [Shelter Protocol](https://shelterprotocol.net/en/introduction/) -The Shelter Protocol is a protocol for creating end-to-end encrypted, federated, user-friendly web applications.
* [Steem blockchain](https://steem.com/)
* [Veilid](https://gitlab.com/veilid/veilid) - Veilid is a peer-to-peer network for easily sharing various kinds of data.
Veilid is designed with a social dimension in mind, so that each user can have their personal content stored on the network, but also can share that content with other people of their choosing, or with the entire world if they want.
* [Waku](https://our.status.im/waku-decentralized-communication-for-web3/) - Decentralized, off-chain communications channel for Web3
* [WebRTC](https://webrtc.org/)
* [Winden](https://github.com/LeastAuthority/winden) - Winden is a free web application for secure, fast, and easy file transfers between devices in real-time. Winden is identity-free, meaning that senders and receivers don't need to know each other's identity to use it, or to reveal their identity. Built on the [Magic Wormhole Protocol](https://magic-wormhole.readthedocs.io/en/latest/).
* [XMTP](https://github.com/xmtp/libxmtp) - A shared library encapsulating the core functionality of the XMTP messaging protocol, such as cryptography, networking, and language bindings. Full decentralization is on the [roadmap](https://xmtp.org/blog/journey-to-decentralization)
* [Zot](https://zotlabs.org/help/en/about/about) - Used in Aether and Hubzilla platforms

#### Decentralized Networking
Decentralized networking/transport libraries and utilities

* [CJDNS](https://github.com/cjdelisle/cjdns) - Encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing
* [GNU:Net](https://gnunet.org/en/) - Private, decentralized networking stack with file sharing, messaging, etc. layers. An official GNU project.
* [LibP2P](https://libp2p.io/) - A decentralized networking stack and library modularized out of The IPFS Project, and bundled separately for other tools to use
* [Tor Onion Services](https://community.torproject.org/onion-services/overview/) - Onion services are services that can only be accessed over Tor. Running an Onion Service gives your users all the security of HTTPS with the added privacy benefits of Tor Browser. Can be used for decentralized applications, see Ricochet Refresh and Quiet listed above.
* [Yggdrasil](https://github.com/yggdrasil-network/yggdrasil-go) - Scalable routing as an encrypted IPv6 overlay network

#### Decentralized and Distributed Databases
* [ClickHouse](https://clickhouse.tech/) - Distributed SQL OLAP DB
* [Cockroach DB](https://github.com/cockroachdb/cockroach) - Distributed SQL DB, which is written in Go and can be compiled to WASM to run on devices
* [CozoDB](https://github.com/cozodb/cozo) - A transactional, relational-graph-vector database that uses Datalog for query. Run on mobile or in the browser.
* [Electric SQL](https://github.com/electric-sql/electric) - Local-first sync layer for web and mobile apps. Build reactive, realtime, local-first apps directly on Postgres
* [FoundationDB](https://github.com/apple/foundationdb) - The open source, distributed, transactional key-value store from Apple.
* [FlockDB](https://github.com/twitter-archive/flockdb) - Distributed graph database in Scala
* [Fluree](https://github.com/fluree/db) - Fluree is an immutable, temporal, ledger-backed semantic graph database that has a cloud-native architecture. It supports a "Data Defending Itself" authorization strategy. (See more below under concepts.) There is a build that [runs in the browser](https://github.com/fluree/fluree-react).
* [Gun](https://github.com/amark/gun) - P2P browser-based graph database. See also above
* [JanusGraph](https://github.com/JanusGraph/janusgraph) - Distributed graph database in Java
* [KVRocks](https://github.com/apache/kvrocks) - Kvrocks is a distributed key value NoSQL database that uses RocksDB as storage engine and is compatible with Redis protocol. No listed webassembly/browser build, but could be possible?
* [mvSQLite](https://github.com/losfair/mvsqlite) - Distributed SQLite that runs on top of FoundationDB.
* [OrbitDB](https://github.com/orbitdb/orbit-db) - Distributed DB implementing CRDTs on IPFS
* [Nebula](https://github.com/vesoft-inc/nebula) - Distributed graph database in C++
* [SQLSync](https://github.com/orbitinghail/sqlsync) - SQLSync is a collaborative offline-first wrapper around SQLite. It is designed to synchronize web application state between users, devices, and the edge.
* [SurrealDB](https://github.com/surrealdb/surrealdb) - A scalable, distributed, embeddable, collaborative, document-graph database, for the realtime web.
* [Tahoe-LAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - Distributed least authority object capabilities database in Python
* [TiDB](https://github.com/pingcap/tidb) - TiDB is an open-source, cloud-native, distributed, MySQL-Compatible database for elastic scale and real-time analytics. Can be run in browser [using webassembly](https://www.pingcap.com/blog/tidb-in-the-browser-running-a-golang-database-on-webassembly/)
* [TiKV](https://github.com/tikv/tikvcozo) - Distributed transactional key-value database, originally created to complement TiDB. Can be [run in browser](https://github.com/bsdelf/tikv-browser)
* [Titan](https://github.com/thinkaurelius/titan) - Distributed graph database in Java

#### Decentralized Search and Indexing
* [Admarus](https://github.com/Mubelotix/admarus) - Peer-to-Peer Search Engine for IPFS
* [Kamilata](https://github.com/Mubelotix/kamilata) - Peer-to-Peer Search Engine System using the Kamilata protocol. Kamilata enables trustless search in open networks. This library can handle any type of data, and be easily integrated into your libp2p application. Powers the Adamarus IPFS search engine.

#### Decentralized AI
AI and machine learning libraries and resources for what is often called "Federated Learning" and sometimes "Decentralized AI" among other terms. AI techniques that can work on data that is separate/private and possibly held on user's edge devices (e.g. smartphones).

* [Awesome Federated Machine Learning](https://github.com/innovation-cat/Awesome-Federated-Machine-Learning#enterprise-grade) - A good "awesome" compendium: Everything about federated learning, including research papers, books, codes, tutorials, videos and beyond. This section in particular links to the most notable "enterprise" quality libraries/frameworks. How can these be adapted for decentralized social media?

* [EdgeML](https://github.com/Microsoft/EdgeML) - This repository provides code for machine learning algorithms for edge devices developed at Microsoft Research India
* [FATE](https://github.com/FederatedAI/FATE) - An Industrial Grade Federated Learning Framework
* [FedLearner](https://github.com/bytedance/fedlearner) - A multi-party collaborative machine learning framework
* [FedML](https://github.com/FedML-AI/FedML) - The federated learning and analytics library enabling secure and collaborative machine learning on decentralized data anywhere at any scale. Supporting large-scale cross-silo federated learning, cross-device federated learning on smartphones/IoTs, and research simulation. MLOps and App Marketplace are also enabled.
* [FederatedScope](https://github.com/alibaba/FederatedScope) - An easy-to-use federated learning platform
* [Flower](https://github.com/adap/flower) - A Friendly Federated Learning Framework, designed to work with edge/mobile devices
* [IBM Federated Learning Lib](https://github.com/IBM/federated-learning-lib) - A library for federated learning (a distributed machine learning process) in an enterprise environment
* [MetisFL](https://github.com/NevronAI/metisfl) - a federated learning framework that allows developers to easily federate their machine learning workflows and train their models across distributed data without ever collecting the data in a centralized location.
* [NVFlare](https://github.com/NVIDIA/NVFlare) - NVIDIA Federated Learning Application Runtime Environment
* [OpenFL](https://github.com/securefederatedai/openfl) - An open framework for Federated Learning
* [PaddleFL](https://github.com/PaddlePaddle/PaddleFL) - Federated Deep Learning in PaddlePaddle
* [SecretFlow](https://github.com/secretflow/secretflow) - A unified framework for privacy-preserving data analysis and machine learning
* [Syft](https://github.com/OpenMined/PySyft) - Perform data science on data that remains in someone else's server
* [TensorFlow Federated](https://github.com/tensorflow/federated) - A framework for implementing federated learning


#### Decentralized Publishing
* [Distributed Press](https://github.com/hyphacoop/api.distributed.press) - An open source publishing tool for the World Wide Web and Distributed Web. It automates publishing and hosting content to the web that it seeds to decentralized protocols like Hypercore and IPFS.

### Common Issues

#### Paying for Storage and Services

A question for all decentralized social networking and collaboration tools is how to pay for the underlying storage and computing cycles needed to support it. Some of the solutions above require you to pay (in one form or another) to "post" content or initiate an action (e.g. most blockchains). Others make no guarantees that your content will be available to others unless you host it yourself and keep your computer constantly on, and then people across the world may be only able to access it very slowly (e.g. IPFS).

#### Secure Communication and Computation

In a world in which the decentralized devices that interact with each other may be low power devices like phones, and in which the security of given nodes in the network may be untrustworthy, it is essential to be able to secure data and also compute on that data securely. This will require end-to-end encryption solutions in which data is encrypted on our individual devices.

It will also require secure _private smart contracts_ and _secure multi-party computation_ that can operate on encrypted data safely and in a "trustless" way. There are various new approaches to this including _trusted execution environments_ and _homomorphic encryption_.

#### Actor Model and Object Capability Access Control

The Actor Model is the most natural framework for building decentralized social protocols, platforms and apps because it aligns with our democratic ideals and ways of initiating and organizing human endeavors. Object Capabilities, as opposed to Access Control Lists (ACLs), builds on the actor model to support the Principle of Least Authority, putting an actor in charge of their data, rather than a recipient or a service. This allows permissions to be revoked by the actor when desired and prevents the Confused Deputy problem and other abuses by service providers and proxies. See the concepts section below for references. See also [ACLs Don't](http://waterken.sourceforge.net/aclsdont/) for an overview of the benefits of Object Capabilities vs ACLs.

#### Development Process Considerations

Even when a project is fully decentralized in its operation and technically open source, its may be tightly controlled by a single corporation. No software that is controlled centrally like this can be considered truly decentralized. Some process considerations to evaluate when considering a project include:

* Is a development roadmap published?
* Is there an open and transparent process for selecting priorities for bug fixes and new features to be added to the development roadmap?
* Are pull requests and code contributions welcomed from everyone? Are pull requests processed in a timely and friendly manner? Are "good first issues" tagged, etc?
* Is there a welcoming Code of Conduct that is published and adhered to?
* Are there open discussion rooms where project maintainers and contributors can be reached with questions and issues in a timely manner?
* Are forks and alternatives welcomed or discouraged?
* Is the project well documented and regularly updated?
* Is the project designed in an extendable way?

### Concepts

Some relevant concepts

* [Actor Model](https://en.wikipedia.org/wiki/Actor_model) - Actor model of decentralized/concurrent computing
* [Attribute Base Encryption](https://crypto.stackexchange.com/questions/17893/what-is-attribute-based-encryption) - Attribute-based Encryption (ABE) allows for implementing
fine-grained decentralized access control based on properties or attributes.
* [Blockchain](https://en.wikipedia.org/wiki/Blockchain)
* [Byzantine Faults](https://en.wikipedia.org/wiki/Byzantine_fault) A type of challenge facing decentralized systems
* [Confidential Computing](https://confidentialcomputing.io/) - A consortium to accelerate the adoption of Trusted Execution Environment (TEE) technologies and standards. See also this list of [current projects](https://confidentialcomputing.io/projects/current-projects/).
* [Confused Deputy Problem](https://en.wikipedia.org/wiki/Confused_deputy_problem)
* [CRDTs](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type) Conflict free replicated data types
* [DAG](https://en.wikipedia.org/wiki/Directed_acyclic_graph) - Directed acyclic graph
* [DAO](https://en.wikipedia.org/wiki/Decentralized_autonomous_organization) Decentralized autonomous organization
* [Data-centric Security](https://en.wikipedia.org/wiki/Data-centric_security) - Also called "Data Defending Itself"
* [Decentralization for Web3 Builders](https://a16zcrypto.com/posts/article/web3-decentralization-models-framework-principles-how-to/) - Specific models and principles of decentralization gleaned from the past several years of working closely with crypto founders, to guide web3 builders tackling what decentralization means in practice, across several use cases
* [Decentralized AI](https://towardsdatascience.com/everything-you-need-to-know-about-decentralized-ai-3abdb052324b)
* [DIDs](https://medium.com/moxystudio/the-need-for-decentralized-identity-4d369408e10e) Decentralized Identifiers
* [DHTs](https://en.wikipedia.org/wiki/Distributed_hash_table) - Distributed Hash Tables
* [Double-ratchet encryption](https://en.wikipedia.org/wiki/Double_Ratchet_Algorithm) - Private messaging with "future secrecy"
* [End-to-End Encryption](https://en.wikipedia.org/wiki/End-to-end_encryption)
* [Federated LEarning](https://en.wikipedia.org/wiki/Federated_learning)
* [Homomorphic Encryption](https://en.wikipedia.org/wiki/Homomorphic_encryption)
* [MegOlm](https://gitlab.matrix.org/matrix-org/olm/blob/master/docs/megolm.md) - A double-ratchet encryption algorithm used by Matrix for private group messaging
* [Object Capability](https://en.wikipedia.org/wiki/Object-capability_model) - An access control approach consistent with the actor model of decentralized/concurrent computing. See also some [introductory slides](http://www.cis.syr.edu/~wedu/Teaching/CompSec/LectureNotes_New/Capability.pdf)
* [P2P](https://en.wikipedia.org/wiki/Peer-to-peer) Peer to peer
* [Principle of Least Privilege](https://en.wikipedia.org/wiki/Principle_of_least_privilege) - Also know as the principle of least authority
* [Privacy-preserving solutions for blockchain](https://www.researchgate.net/publication/336937331_Privacy-Preserving_Solutions_for_Blockchain_Review_and_Challenges) - A good survey and overview of privacy-preserving solutions for blockchains
* [Privacy-preserving DHTs, status](https://github.com/gpestana/notes/issues/8). See also [this paper](https://github.com/gpestana/p2psec/tree/master/papers/privacy_preserving_dht) on current reality and future
* [Self-sovereign identity](https://en.wikipedia.org/wiki/Digital_identity#Self-sovereign_identity)
* [Secret contracts](https://blog.enigma.co/defining-secret-contracts-f40ddee67ef2) - A form of secure multi-party computation. Privacy protecting smart contracts. Also sometimes called "private contracts" or "private smart contracts"
* [Smart contracts](https://en.wikipedia.org/wiki/Smart_contract)
* [SMC](https://en.wikipedia.org/wiki/Secure_multi-party_computation) - Secure multi-party computation
* [Sybil attacks](https://en.wikipedia.org/wiki/Sybil_attack) - A type of attack on a decentralized system
* [TEEs](https://en.wikipedia.org/wiki/Trusted_execution_environment) Trusted execution environments, used in current versions of secure/private smart contracts
* [Verifiable Credentials](https://en.wikipedia.org/wiki/Verifiable_credentials)
* [zk-SNARKs and zk-STARKs](https://en.wikipedia.org/wiki/Non-interactive_zero-knowledge_proof) - Non-interactive zero-knowledge proofs. zk-SNARKS require trusted third-party setup, zk-STARKs do not. The [Moonmath Manual](https://github.com/LeastAuthority/moonmath-manual) seeks to make ZK math understandable to a broader audience.

### Related Awesome Lists
* [Decentralized ID](https://github.com/Decentralized-ID/decentralized-id.github.io)
* [Fediverse](https://github.com/emilebosch/awesome-fediverse)
* [Object Capabilities](https://github.com/dckc/awesome-ocap)
* [Peer-to-Peer](https://github.com/kgryte/awesome-peer-to-peer)
* [Self-Hosted](https://github.com/awesome-selfhosted/awesome-selfhosted)

### Initiatives and Institutions
* [Next Generation Internet](https://www.ngi.eu/) - a major European initiative and funder for a Human Internet that respects the fundamental values of privacy, participation and diversity.

### Roadmap
This is a work in progress! Please help extend it and keep it up to date.

It is hoped that in the future a comparison of the various apps and platforms will be provided. Some of the criteria that will be worth highlighting are:
* Availability / use of encryption
* Privacy and management of personal data
* Underlying technologies used
* Adoption and use
* Level of maintenance and ongoing development
* License type
* Features provided
* Ability to do financial transactions
* Sponsors / contributors
* Degree of _lock in_ that prevents leaving or migrating from the app / platform
* Degree of integration available with other networks and tools
* Performance / speed


### Contributions
Contributions aligned with the stated purpose and consistent with our [code of conduct](https://www.contributor-covenant.org/version/1/4/code-of-conduct) are welcome! Make a pull request to suggest additional resources or enhance this document. Edits to pull requests may be requested for placement, accuracy. Contributions that highlight the criteria mentioned in the roadmap above are especially appreciated.


### License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.