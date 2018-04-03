---
title: Appendix F
layout: page
permalink: /appendices/F/
---

# Appendix F – Blockchain Technology Criteria10
## Blockchain Scalability and Volume
The scalability of a particular blockchain network type determines the maximum transaction throughput (number of transactions processed per second) and the maximum volume of transactions that can be processed within a reasonable performance criteria, with a growing blockchain.

The scalability of a blockchain is impacted by the volume of transactions processed on blockchain, size limit of a block, size of entire blockchain, number of verifying nodes to provide consensus, time taken to process a transaction, high processing fee to be paid for transactions processing, etc.

A public permissionless blockchain can have unlimited number of participants to join in network and perform read and write transactions without any censorship resistance and thus the blockchain scalability is majorly constrained due to very large volume of transactions and big blockchain size.

Bitcoin blockchains are much less scaled compared to Ethereum network as there is a built-in hard limit of one megabyte per block (10 minutes to mine a new block) compared to Ethereum which takes maximum 20 seconds. Furthermore, there is a cost to performing certain actions on the public Bitcoin or Ethereum networks. BTC spending per transaction is high in Bitcoin compared to ‘gas price’ per transaction processing required in Ethereum.

Permissioned blockchains have comparatively much lesser blockchain size as participation is controlled and consensus is done using identified selected blockchain notary nodes. The consensus delay is much lower than that in public blockchains. The scalability of a blockchain grows linearly with addition of more hardware. Thus, permissioned blockchains can better scale up by using more storage and addition of peer nodes in P2P network.

## Upgradability
What is the record of accomplishment of the developers for delivering enhancements and upgrades to the blockchain?

Tools needed to verify transactions may change over time and thus the steps and associated cost to upgrade those tools should be a consideration. The ability to keep up with changes will be dependent on the ability to accomplish enhancements and upgrades to the blockchain without disrupting or corrupting the blockchain itself. While blockchain applications appear endless, the software security and manageability procedures are a significant concern for future concept design.

Upgradability of blockchain as a service could be costly. This is especially true if existing platforms cannot keep pace with or are incompatible with emerging blockchain or middleware technology. 

Due to the volatile Financial Technology (FINTECH) market, new technologies could be cost prohibitive, and with their own inherent security risks. This could be one of the biggest and most challenging concerns in using a technology like blockchain and the investment which may lose its luster if it costs too much to afford the upgrades.

## Speed and Latency
The blockchain speed is the transaction throughput (maximum number of TPS) which is determined by the block size and the consensus delay. It does not matter if a blockchain is public or private, the speed of each transaction will be based on the processing power of the network in which the algorithm is placed, and the particular type of encryption protocol. As public blockchains have larger number of verifying nodes that are involved in verifying the transactions, the consensus delay is much higher compared to permissioned networks where consensus is achieved by lessor number of verifying nodes (blockchain notaries or identified incentivizing nodes) and has much less latency due to consensus delay and thus high speed. Most of the permissioned networks implement Byzantine tolerance consensus protocol which does not require consensus from every participating node and provide high transaction processing speed.

The size of the block is what makes the difference. By decreasing the size of the transaction or packing more transactions into one block, the faster and more processing power that will be behind it. The speed of transaction processing on a particular blockchain is further determined by any hard limit set on maximum block size. Bitcoin has a hard limit of one megabyte on a block set which causes a latency of 10 minutes compared to 10-20 seconds of latency in Ethereum network. The ability to quantify how you validate the speed of any transactions appears to still be subjective on the network, the size of the block, etc.

## Security and Immutability
The documented level of confidence of security within the blockchain is high. The blockchain itself is inherently resistant to threats while the off-chain applications are not. The blockchain is a mathematically certain way to protect data in both the public and private applications. This certainty is accomplished with the use of the three basic science and mathematical concepts include hashing, keys, and digital signatures.

A public blockchain network is completely open and anyone can join and participate in the network. The blockchain network typically has an incentivizing mechanism to encourage more participants to join the network. Bitcoin is one of the largest public blockchain networks in production today. In a public-facing blockchain, administrators or those responsible for the upkeep and management of the blockchain, must have the ability to see the transactions “in- action” as they are taking place. A blockchain, by design, allows a database to be shared between entities who do not fully trust each other, without central administration. All blockchains suffer from the same fundamental issue, the content of every transaction is revealed to every participant. This transparency is necessary in order to verify a transaction by every node associated with the blockchain. Conversely, conventional/centralized database transactions are only visible to creators and administrators.

One of the drawbacks of a public blockchain is the substantial amount of computational power that is necessary to maintain a distributed ledger at a large scale. More specifically, to achieve consensus, each node in a network must solve a complex, resource-intensive cryptographic problem called a PoW to ensure all are in sync and thus immutability is very high. The disadvantage is the openness of public blockchain, which implies little to no privacy for transactions and only supports a weak notion of security. Both of these are important considerations for enterprise use cases of blockchain.

A private blockchain network requires an invitation and must be validated by either the network starter or by a set of rules put in place by the network starter. Businesses who set up a private blockchain, will generally set up a permissioned network. This places restrictions on who is allowed to participate in the network, and only in certain transactions. Participants need to obtain an invitation or permission to join. The access control mechanism could vary: existing participants could decide future entrants; a regulatory authority could issue licenses for participation; or a consortium could make the decisions instead. Once an entity has joined the network, it will play a role in maintaining the blockchain in a decentralized manner. Thus immutability of DLT in permissioned blockchains is largely controlled by set of access permission rules and the industry level protocols to achieve consensus with known number of verifying nodes and also most of the participants are trusted users only. Data privacy is better managed by defining read and writes level access permissions for each user in permissioned blockchains.

## Storage and Structural Needs
The permissionless blockchain has always untrusted participants and to maintain immutability of transactions stored in blockchain, consensus is required by all participant nodes involved in the blockchain thus the distributed ledgers are shared with all complete blockchain blocks downloaded in a decentralized manner at all participant nodes with greater computational power needed to validate the transactions. Thus, blockchain size is too large and more number of transactions are processed. Thus, the scalability of permissionless blockchain is managed by adding more storage and processing servers in permissionless blockchains compared to permissioned blockchains where participation is controlled and the consensus size is less as all participant nodes are not required to validate transactions to ensure immutability of distributed ledger but only selected nodes does the transaction validation.

The following table lists the common use cases that are suited for each type of blockchain.

|Primary Purpose|Type of Blockchain|
|--|--|
|Move value between untrusted parties|Public|
|Move value between trusted parties|Private|
|Trade value between unlike things|Permissioned|
|Trade value of the same thing|Public|
|Create decentralized organization|Public or permissioned|
|Create decentralized contract|Public or permissioned|
|Trade securitized assets|Public or permissioned|
|Build identity for people or things|Public|
|Publish for public record keeping|Public|
|Publish for private recordkeeping|Public or permissioned|
|Perform auditing of records or systems|Public or permissioned|
|Publish land title data|Public|
|Trade digital money or assets|Public or permissioned|
|Create systems for IoT security|Public|
|Build system security|Public|

There may be exceptions depending on project and it is possible to use a different type of blockchain to reach the project goal.

## Operational Considerations, Tools, and Monitoring
The blockchain protocol defines three functional roles an entity can play on a blockchain network:
- Asset Issuers – define and issue digital assets.
- Account Managers –Custody and transfer assets.
- Observers – receive blocks and view blockchain data but do not create transactions.

Corporations, brands, merchants, and governments can act as asset issuers. Custodians and banks can transform into account managers on a blockchain network. Meanwhile regulators and risk managers can reinvent their roles with real-time insight and perfectly auditable records.

Any entity running a blockchain network can participate in one or multiple of these roles. The firm that launches a blockchain network in market, is called as operator of that blockchain. Exchanges, brokers, payments networks or government agencies are examples of entities that adopt the responsibility of network operators.

Network operators perform following four functions on a network:
- Determine who can participate in the network.
- Gather signed transactions from participants.
- Generate and sign blocks of these valid transactions.
- Distribute blocks to participants.

A block is valid when it is signed by a quorum of block signers in a process called federated consensus. All members of the network know the identities of block signers and accept blocks only if they have been approved by a threshold number of block signers.

Each network participant can also cryptographically validate the whole chain of transactions. This consensus process ensures that competing transactions are resolved and guarantees that transactions are final. In order to operate or participate in a blockchain network, an entity runs a node in the network.

Implementation can be based on open source blockchain protocol or using proprietary blockchain platform or services. The nodes in the permissioned network are designed to run in enterprise IT environments. In case of public permissionless blockchain implementations, complete blockchain node chain is deployed on participant machines in decentralized manner and each machine acts as node connected with other nodes to form Internet of Value.

Any blockchain network operator manages following layers of implementation:
- Storage Layer – stores global blockchain data as well as local account data.
- Services Layer - services layer is on top of storage layer that allows creation of assets and transactions.
- Communication layer – consists of API that connects applications and link nodes together.
- SDK layer – allows developers to create applications on top of stack.

The major considerations in operating a blockchain network are security, performance throughput and scalability.
- Proper network management and rotation of key material is required to secure digital assets.
- Industry standard hardware security modules (HSM) technology should be integrated with blockchain network to secure the blockchain nodes and transaction signing. Multi- signature accounts using independent HSMs could further increase security.
- The deployment model of blockchain network should be based on vertical scaling of server resources as well as scaling blockchain horizontally over several servers, deployed across many data centers. The linear scale out strategy for increasing scalability by addition of more hardware would provide a very scalability of blockchain network with a high availability.
- The communication and service layer should follow stateless architecture so that high availability could be simply achieved by simple addition of active redundant servers.
- All new features should undergo rigorous performance testing and optimization to ensure optimized resource utilization and high throughput.
- The high availability of storage layer should be achieved with a combination of synchronous and asynchronous replication together with a simple failover scheme.
- The application requests should be load balanced across the communication and services layer and data should be replicated and sharded across storage layer to achieve high performance and high availability.
- Blockchain platforms are not just data management platforms but need to be integrated with enterprise integration adaptors and identity management platforms to provide specialized DApps based functionalities built upon blockchain network. So there is a need to implement EAI patterns based interoperability standards in designing middleware for blockchain applications.
- Tool based monitoring of blockchain network is important to monitor blockchain transaction activities and detect any suspicious or maligning activities.
- Using blockchain explorers (Etherscan.io, Etherchain.org, Digix, Augur, etc.) for quickly checking transaction or a specific smart contract activity is acceptable. But it gets complex when you want to do real monitoring on the long run as:
    - There is no control on what is scanned or what information.
    - The service is not local, so you are at risk any moment the service is not available. o Since these explorers take the task of monitoring and reporting activity about the whole blockchain you will end up with some restrictions. Etherscan, for example does not process requests that return more than 10,000 transactions.
    - The solution is to create a local tool that can run on blockchain network or server that will monitor specific addresses you specify and return the whole activity they conduct.
- High availability and disaster recovery planning should be provisioned to ensure the critical service availability during network failure.

The blockchain operator should maintain a robust and up to date and internal knowledgebase repository and resources with right skillset to manager blockchain network and operations effectively.

## Performance Considerations – Benchmarks
Most of the blockchain vendors claim performance of blockchain network in terms of TPS. According to the claim of fabric, 100,000 TPS is the aim to achieve if there are about 15 validating nodes running in proximity in Hyperledger fabric blockchain network. However as per the results of past performance stress tests done in fabric environment using the simplest example of running chaincode on 4 peer nodes running on different servers in close proximity, query performance for each peer could reach 7000 QPS per second, while the simple invoke performance for each peer was only 700 TPS (benchmark hardware environment: Intel(R) Xeon(R) CPU E5-2620 v3 @ 2.40GHz 64G DRAM 1T SATA Disk).

Blockchain throughput is linearly scalable by addition of more peer nodes. However even if the throughput could be linear scalable, the peak TPS of current system would be only 10,000 on P2P networking of 15 nodes, which is only 1/10 of the claim made by fabric. This due to the fact that the overhead of PBFT consensus would grow exponentially with the increasing number of nodes offsetting the linear scaling factor of blockchain throughput with addition of more nodes.

The TPS performance of blockchain is largely impacted by following three factors:
- Total Number of nodes in blockchain network as blockchain scalability linearly scales with addition of more nodes in P2P network.
- Total number of nodes involved in consensus to validate a transaction as consensus delay exponentially grows with more number of nodes participating in consensus validation.
- Type of consensus protocol used in validation of transaction by verifier nodes.

The consensus delay is the most impacting factor in determining the performance of a blockchain network. For example, it’s evident that scaling the number of nodes in a broadcast network using a probabilistic consensus protocol such as PoW presents an enormous scaling barrier.

This has motivated a number of platform builders, including R3, to consider “performance and scalability” in their platform designs. For example, Corda limits the consensus interaction to only the parties involved in a particular transaction, along with the consensus pool needed to verify uniqueness, and validate the contract if requested. Other platforms such as Hyperledger Fabric V1.0 have also taken a bespoke approach to minimizing transaction sharing. Of course, the primary reason for restricting transaction sharing is “privacy” under the principle “the best way to keep a secret is to not share it.” However, this policy does also provide ancillary performance benefits. Some might debate the loss of network resiliency in such a restrictive model.

Some of the blockchain network vendors like Corda delegates the task of validating transactions to pool of selected notes (Consensus Notary pools). These Notary pools provide a uniqueness service by operating consensus over uniqueness by nodes operated by a set of distrusting entities.

A notary consensus pool could differ by the protocol configuration, and by their size (number of notary nodes in the pool), and their location (for a given pool, notary node location could be in any geographic location) which may impact the performance of a blockchain network.

Blockchain’s performance is further determined by the number of transactions in a block (block size) and the time between blocks (dwell time). Playing with parameters by increasing block size, decreasing transaction size, or dwell time can provide a significant one-time boost and optimize blockchain for today’s network,

The performance of a blockchain application is also determined by the architecture of storage, services and interoperability layer, and the capacity of the hardware used and the network used to connect the peer nodes.

The mining volume is an additional constraint for Ethereum, as serialising mining as Bitcoin does, limits the number of computations per block. Sharding an Ethereum chain might improve its performance as it would enable smart contracts to be processed in parallel.

Open source Hyperledger “Caliper” project could be used to conduct performance benchmarking on a given blockchain network, before deciding on a particular vendor choice. The tool is designed for Hyperledger but is platform agnostic and can be used with any other blockchain network.

## Blockchain Notaries
An asset issuer using blockchain infrastructure is not generally required to process transactions or to write data to the blockchain – this task could be delegated to blockchain notaries. Notaries could be either known entities (in permissioned blockchains), or any users satisfying technical capabilities imposed by a blockchain consensus algorithm (in permissionless blockchains).

Permissioned blockchains could be more beneficial for financial institutions in the short term because of the flexibility of the blockchain specification and increased compliance. On the other hand, permissionless blockchains could prove more attractive for consumer-to-consumer markets and IoT applications because of inherent trustlessness and permissionless entry and exit.

Blockchain notaries get revenue incentives by keeping blockchain safe e.g. by running services in top of it. For Chain protocol, the Consensus Notary pools (e.g. RAFT, BFT-SMaRT, etc.) provide a unique service by operating consensus over uniqueness by nodes operated by a set of distrusting entities.

A notary consensus pool could differ by the protocol configuration, and by their size (number of notary nodes in the pool), and their location (for a given pool, notary node location could be in any geographic location). The size of notary consensus pool determines the performance (TPS) of a blockchain as it directly impact the consensus delay in verifying the transactions.

## Blockchain Network
A public blockchain network provides three security modes for constituent nodes:
- Full verification nodes that verify and store every transaction circulating in the network. This security mode could be used by blockchain notaries, regulators, auditors, analytical services and dedicated “blockchain as a service” providers
- Simplified payment verification (SPV) nodes, which would be used by a vast majority of end users, as this security mode requires little computational resources and memory space
- Partial verification nodes made possible with the help of segregated witness and fraud
proofs. These nodes could verify a small percentage of transactions (e.g. 1%), while contributing to the overall security of the blockchain network. Partial verification nodes could be operated by service providers on the blockchain

In the case of a blockchain with restricted read access, the architecture of the blockchain network would be determined by transaction processors. For example, transaction processors could operate full nodes, and all other users could be provided to concerning transactions either through SPV network nodes or through equivalent web application interfaces. Thus, blockchains with restricted access could be less scalable or reliable because of uneven distribution of transaction processing.

There is an important distinction between SPV nodes and web API access to blockchain data. While SPV nodes do not increase the security of the blockchain network, their use together with the publicly available chain of block headers could provide uniqueness of blockchains and immutability of data as any change would not be accepted by SPV nodes. Alternatively, same thing could be achieved by PoW consensus. In the case that access to the blockchain is provided via web APIs without disclosing the blockchain structure, reliably proving uniqueness and immutability becomes more difficult. Even if the regulator or an auditor would have complete access to the blockchain (e.g. by operating a full verification node), data provided to the regulator could differ from data served via API as a result of an eclipse attack performed by colluding blockchain notaries.

## User Authentication and Authorization
User authorization in blockchain is performed using public key cryptography. In the simplest case, blockchain-based assets are bearer assets (i.e., the ownership of an asset is determined by the knowledge of a private key.) Two-factor authentication or other security measures comparable to those of centralized e-money systems could be implemented by using dedicated wallet services.

Security properties of public key cryptography could be boosted by the use of specialized hardware wallets for signing transactions. In order to maintain user privacy, blockchain users could utilize hierarchical deterministic wallets and the pay-to-contract protocol.

In the case of more complex transaction models, e.g. for smart contracts, zero knowledge proofs, and secure multi-party computations could be used in order to execute contracts while not disclosing data to any of computers.

## Asset Issuance
As asset issuance is a special type of transactions, the identity of the issuer could be determined according to the general user identification rules (using the blockchain-based PKI or other techniques).

A regulatory body could explicitly acknowledge asset issuance by co-signing the corresponding transaction together with the issuer, or by granting the issuer a special kind of the digital certificate.

An asset could be marked as locked; meaning the assets of the same type cannot be issued in the future by anyone, including the initial issuer. This type of assets is useful (e.g. for creating non- dilutable shares).
- An asset could be marked as divisible to several decimal places (cf. with Bitcoin, which is divisible to 8 decimal places).
- An asset could be made non-transferable in order to limit secondary market (e.g. due to regulation requirements).
- Additional metadata could be associated with the asset, either directly or in the form of a hash commitment. In the second case, off-chain data could be retrieved with the help of distributed hash tables, e.g., implemented using IFSC or Bit Torrent protocol. Metadata could be useful in implementing event tickets, for example.