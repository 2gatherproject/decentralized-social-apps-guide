## Awesome Decentralized, Open-Source Social Networking and Collaboration Applications and Platforms

### Contents
* [Purpose](#purpose)
* [Applications and Platforms](#applications-and-platforms)
    * [Social Networking](#social-networking)
    * [Collaboration](#collaboration)
    * [Identity](#identity)
    * [Decentralized Protocols](#decentralized-protocols)
    * [Decentralized Databases](#decentralized-databases)
* [Common Issues](#common-issues)
* [Concepts](#concepts)  
* [Related Awesome Lists](#related-awesome-lists)  
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

* [Aether](https://getaether.net/) - Open source, self-governing communities with auditable moderation and mod elections
* [Briar](https://briarproject.org/) - WhatsApp clone with security focus. GPL licensed
* [Element](https://element.io/), formerly known as Riot IM, is the reference messaging client for the Matrix platform. Matrix is currently federated but a fully decentralized version is under active development (see below). Strongly private group messaging using MegOlm double-ratchet. Backed by [Automattic](https://matrix.org/blog/2020/05/21/welcoming-automattic-to-matrix), the creators of Wordpress, among others. Used by the [French](https://matrix.org/blog/2018/04/26/matrix-and-riot-confirmed-as-the-basis-for-frances-secure-instant-messenger-app) and [German](https://www.heise.de/newsticker/meldung/Bundeswehr-setzt-kuenftig-auf-Matrix-als-Messenger-4719474.html) governments and other clients. Apache 2.0 licensed
* [DTube](https://d.tube/) - Youtube clone using Steemit blockchain and IPFS. GPL licensed
* [Iris](https://irislib.github.io/) - Social sharing using Gun and IPFS
* [Jami](https://jami.net/) - WhatsApp clone
* [Junto](https://junto.foundation/) - Social network on Holochain
* [Lemmy](https://github.com/LemmyNet/lemmy) - An alternative to Reddit. Curently only federated, but because it is in Rust it could be ported to WASM and made fully decentralized, like Matrix (see below)
* [Peerpeth](https://peepeth.com/welcome) - Twitter clone on the Ethereum blockchain
* [PeerTube](https://joinpeertube.org/en/) - Youtube clone using ActivityPub
* [Patchwork](https://github.com/ssbc/patchwork) - Social network on Secure Scuttlebut. AGPL licensed
* [Textile Photos](https://github.com/textileio/photos) - A photo sharing app using Textile (See below)


##### Platforms

* [3box](https://3box.io/) Nascent social networking platform using Ethereum and OrbitDB (IPFS-based)
* [Mix platform](https://www.mix-blockchain.org/) - Using Ethereum and IPFS
* [Matrix platform](https://matrix.org/) - Matrix is an extendable social messaging platform that is currently federated/distributed, but they are looking into a [fully decentralized P2P version](https://fosdem.org/2020/schedule/event/dip_p2p_matrix/) with an innovative approach that puts the federated server onto people's devices! Something to watch - A [discussion room](https://matrix.to/#/#p2p:matrix.org) is available to follow developments. Strongly private group messaging using MegOlm double-ratchet. Supports [bridges](https://matrix.org/bridges/) to existing "walled garden" corporate networks and custom [bots](https://matrix.org/bots/). Matrix is governed through an transparent, participatory process overseen by the [Matrix Foundation](https://matrix.org/foundation/). Element is Matrix's reference client (see above).
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
* [Aragon platform](https://aragon.one/)
* [DAOStack platform](https://daostack.io/)
* [Colony platform](https://colony.io/)
* [Moloch platform](https://github.com/MolochVentures/moloch)

###### Ethereum, other

* [BroncoVotes](https://github.com/pmarella2/BroncoVotes) - Ethereum based secure voting platform
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
* [Trellis](https://github.com/automerge/trellis) - Trello clone based on MPL (Automerge & WebRTC)

##### Meta
* An overview of existing Ethereum-based DAO (decentralized autonomous organization) platforms (6/16/19): [Aragon, DAOStack, Colony, Moloch](https://kronosapiens.github.io/blog/2019/06/16/aragon-daostack-colony-moloch.html)

#### Identity

Identity services are a key requirement of most social/collaborative apps. Decentralized and self-sovereign identity platforms and "wallets" are listed here.

* [DID-SIOP](https://identity.foundation/did-siop/) - OpenID protocol for self-issued (self-sovereign) identities, e.g. using a public/private key or cryptography wallet
* [Ceramic](https://www.ceramic.network/) DIDs and linked documents on IPFS. Affiliated with 3Box and Ethereum ecosystem. (Not affiliated with Decentralized Identity Foundation?)
* [IDM](https://github.com/ipfs-shipyard/pm-idm) General purpose identity manager for DIDs
* [iden3](https://iden3.io/) Ethereum identity platform leveraging zk-SNARKs (See below)
* [ION](https://github.com/decentralized-identity/ion) DID Method implementation using the Sidetree protocol on top of Bitcoin. From [Decentralized Identity Foundation](https://identity.foundation/).
* [ipid](https://github.com/jonnycrunch/ipid) - DIDs using IPFS
* [Hyperledger Indy](https://www.hyperledger.org/projects/hyperledger-indy)
* [Keycard](https://keycard.tech/) - A new type of smartcard and open source API for simple integration with crypto wallets, DApps, and hardware
* [MetaMask](https://metamask.io/) Ethereum wallet/identity manager
* [Reclaim:ID](https://reclaimid.gitlab.io/) - Decentralized identity on GNU:net with OpenID interface
* [Status.im](https://status.im/) - Status is a secure messaging app, crypto wallet, and Web3 browser
* [Trezor](https://trezor.io/) Open-source hardware wallet/identity manager
* [uPort](https://www.uport.me/) Ethereum wallet/identity manager
* [Wallet Connect](https://walletconnect.org/) - Open protocol for connecting Wallets to Dapps

##### Meta
* [Decentralized Identity Foundation](https://identity.foundation/)
* [Decentralized Web Developer Survey 2020](https://medium.com/fluence-network/decentralized-web-developer-report-2020-5b41a8d86789)

#### Decentralized Protocols
These are the underlying decentralized protocols powering the dapps and platforms above

* [ActivityPub](https://activitypub.rocks/)
* [Automerge](https://github.com/automerge/automerge) - CRDT implementation
* [Bitcoin blockchain](https://bitcoin.org/en/)
* [BitTorrent](https://en.wikipedia.org/wiki/BitTorrent)
* [Dat](https://www.datprotocol.com/) - A mutable, identity addressed file/data sharing protocol
* [Enigma](https://enigma.co/) - Secure "secret contract" protocol extended from Ethereum. Founders of [Secret Network](https://scrt.network/)
* [Ethereum blockchain](https://www.ethereum.org/)
* [GNU:Net](https://gnunet.org/en/) - Private, decentralized networking stack with file sharing, messaging, etc. layers. An official GNU project.
* [Gun](https://github.com/amark/gun) - P2P CRDT protocol implementation
* [Holochain](https://holochain.org/)
* [LibP2P](https://libp2p.io/)
* [IPFS](https://ipfs.io/) - An immutable, content addressed file/data sharing protocol. libp2p based
* [MPL](https://github.com/automerge/mpl) - Using Automerge and WebRTC
* [Oasis](https://www.oasislabs.com/) - Secure "secret contract" protocol extended from Ethereum
* [OrbitDB](https://github.com/orbitdb/orbit-db) - Distributed DB implementing CRDTs on IPFS
* [Secure Scuttlebut](https://www.scuttlebutt.nz/)
* [Steem blockchain](https://steem.com/)
* [WebRTC](https://webrtc.org/)
* [Zot](https://zotlabs.org/help/en/about/about) - Used in Aether and Hubzilla platforms

#### Decentralized Databases
* [ClickHouse](https://clickhouse.tech/) - Distributed SQL OLAP DB
* [Cockroach DB](https://github.com/cockroachdb/cockroach) - Distributed SQL DB, which is written in Go and can be compiled to WASM to run on devices
* [FlockDB](https://github.com/twitter-archive/flockdb) - Distributed graph database in Scala
* [Gun](https://github.com/amark/gun) - P2P browser-based graph database. See also above
* [JanusGraph](https://github.com/JanusGraph/janusgraph) - Distributed graph database in Java
* [Nebula](https://github.com/vesoft-inc/nebula) - Distributed graph database in C++
* [Tahoe-LAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - Distributed least authority object capabilities database in Python
* [Titan](https://github.com/thinkaurelius/titan) - Distributed graph database in Java

### Common Issues

#### Paying for Storage and Services

A question for all decentralized social networking and collaboration tools is how to pay for the underlying storage and computing cycles needed to support it. Some of the solutions above require you to pay (in one form or another) to "post" content or initiate an action (e.g. most blockchains). Others make no guarantees that your content will be available to others unless you host it yourself and keep your computer constantly on, and then people across the world may be only able to access it very slowly (e.g. IPFS).

#### Secure Communication and Computation

In a world in which the decentralized devices that interact with each other may be low power devices like phones, and in which the security of given nodes in the network may be untrustworthy, it is essential to be able to secure data and also compute on that data securely. This will require end-to-end encryption solutions in which data is encrypted on our individual devices.

It will also require secure _private smart contracts_ and _secure multi-party computation_ that can operate on encrypted data safely and in a "trustless" way. There are various new approaches to this including _trusted execution environments_ and _homomorphic encryption_.

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
* [Blockchain](https://en.wikipedia.org/wiki/Blockchain)
* [Byzantine Faults](https://en.wikipedia.org/wiki/Byzantine_fault) A type of challenge facing decentralized systems
* [Confidential Computing](https://confidentialcomputing.io/) - A consortium to accelerate the adoption of Trusted Execution Environment (TEE) technologies and standards
* [CRDTs](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type) Conflict free replicated data types
* [DAG](https://en.wikipedia.org/wiki/Directed_acyclic_graph) - Directed acyclic graph
* [DAO](https://en.wikipedia.org/wiki/Decentralized_autonomous_organization) Decentralized autonomous organization
* [DIDs](https://medium.com/moxystudio/the-need-for-decentralized-identity-4d369408e10e) Decentralized Identifiers
* [Double-ratchet encryption](https://en.wikipedia.org/wiki/Double_Ratchet_Algorithm) - Private messaging with "future secrecy"
* [Decentralized AI](https://towardsdatascience.com/everything-you-need-to-know-about-decentralized-ai-3abdb052324b)
* [End-to-End Encryption](https://en.wikipedia.org/wiki/End-to-end_encryption)
* [Homomorphic Encryption](https://en.wikipedia.org/wiki/Homomorphic_encryption)
* [MegOlm](https://gitlab.matrix.org/matrix-org/olm/blob/master/docs/megolm.md) - A double-ratchet encryption algorithm used by Matrix for private group messaging
* [Object Capability](https://en.wikipedia.org/wiki/Object-capability_model) - An access control approach consisten with the actor model of decentralized/concurrent computing
* [P2P](https://en.wikipedia.org/wiki/Peer-to-peer) Peer to peer
* [Self-sovereign identity](https://en.wikipedia.org/wiki/Digital_identity#Self-sovereign_identity)
* [Secret contracts](https://blog.enigma.co/defining-secret-contracts-f40ddee67ef2) - A form of secure multi-party computation. Privacy protecting smart contracts. Also sometimes called "private contracts" or "private smart contracts"
* [Smart contracts](https://en.wikipedia.org/wiki/Smart_contract)
* [SMC](https://en.wikipedia.org/wiki/Secure_multi-party_computation) - Secure multi-party computation
* [Sybil attacks](https://en.wikipedia.org/wiki/Sybil_attack) - A type of attack on a decentralized system
* [TEEs](https://en.wikipedia.org/wiki/Trusted_execution_environment) Trusted execution environments, used in current versions of secure/private smart contracts
* [Verifiable Credentials](https://en.wikipedia.org/wiki/Verifiable_credentials)
* [zk-SNARKs and zk-STARKs](https://en.wikipedia.org/wiki/Non-interactive_zero-knowledge_proof) - Non-interactive zero-knowledge proofs. zk-SNARKS require trusted third-party setup, zk-STARKs do not.

### Related Awesome Lists
* [Decentralized ID](https://github.com/Decentralized-ID/decentralized-id.github.io)
* [Object Capabilities](https://github.com/dckc/awesome-ocap)
* [Peer-to-Peer](https://github.com/kgryte/awesome-peer-to-peer) 
* [Self-Hosted](https://github.com/awesome-selfhosted/awesome-selfhosted)

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