---
title: Appendix B
layout: page
permalink: /appendices/B/
---

# Appendix B – Deployment Models and Common Use Cases
## Deployment Models Pros and Cons
### Multiple, Separate Blockchains for Assets
Each digital asset or a set of assets maintained by the same issuer could potentially have its own blockchain, either permissionless or permissioned. Merged mining allows securing multiple blockchains with the same computational resources. However merged mining in a permissionless environment could be unsafe, as an attacker with enough hash power could deliberately mine empty blocks or otherwise disrupt transaction processing. A permissioned blockchain could be more resilient to attacks, but it would still have a single point of failure in the form of a single transaction processor. From the auditing and regulating points of view, properties of an issuer- managed blockchain could be similar to existing asset management systems. The cost of operating an issuer-specific blockchain (either on-site or using a Platform as a service (PaaS)) could be comparable to traditional asset management systems because of the need to develop end-user applications (such as wallet services with secure authentication, accounting tools, etc.) Additionally, using multiple blockchains could complicate the development of third-party applications and diminish the network effect by requiring additional tools to interact with other digital assets.

### Colored Coin Protocols
Colored coin protocols share the user authentication model with the underlying blockchain. However, because the validity of colored coin transactions is not checked by the blockchain network, colored coin protocols lack efficient payment verification methods. Colored coin protocols using Bitcoin blockchain include ChromaWay, Open Assets, and Colored Coins Protocol.

### Metacoins
A metacoin system could provide automated order-matching for trading asset pairs, dividend payments, and so on. Metacoin systems may utilize a dedicated cryptocurrency as a means of payment for provided services. Metacoin systems on top of the Bitcoin blockchain include OmniLayer, Counterparty, and CoinSpark.

### Multi-Asset Blockchains
Compared to other deployment models, multi-asset blockchains have more space-efficient proofs of ownership, as simplified payment verification could be utilized for all natively supported blockchain assets. On the other hand, known mechanisms of sharing blockchain security (merged mining and blockchain anchoring) pose security risks in permissionless context. The federated governance model puts the greater responsibility on the blockchain maintainers. As the maintainers can effectively determine the state of the blockchain, they could be legally obliged to be able to reverse transactions, freeze funds, etc. by the regulatory bodies. A multi-asset blockchain could be integrated into existing blockchain infrastructure by using sidechain8 technology. Smart property represents the ownership of real-world objects with the help of blockchain data. For example, a blockchain-enabled car would operate only if the driver holds the blockchain-based ownership token.

### Smart Contracts
User-defined assets could be represented with the help of a smart contract on a smart contract blockchain (e.g. Ethereum blockchain). The contract could store the mapping of the addresses of current holders of the asset to the corresponding balances. These balances could be updated with the help of messages sent to the contract encoding asset transfer or issuance. The contract could use the conventional authorization scheme of the underlying blockchain in order to check transfer and issuance permissions or could specify new rules for asset transactions.

## Use Cases of Blockchain Digital Assets
### Complex Financial Assets
Digital assets could represent publicly traded financial assets (e.g. securities). These assets require a high level of security, are heavily regulated, and used in business-to-business contexts, therefore requiring permissioned blockchains, at least in the short term. Permissionless blockchains could be useful for novel financial services, such as crowd funding.

### Smart Property
Asset ownership could be transferred using a transaction with an input bearing the token. Smart property assets would have slow transaction velocity and would require security before scalability. Therefore, smart property could plausibly be implemented with the help of dedicated ownership protocols on top of highly secure public blockchains, which do not necessarily support the concept of smart property natively.

### Electronic Money
Digital assets could represent e-money, such as alternative currencies (e.g. local currencies or in- game currencies) or claims of fiat money. Electronic money pegged to real-world currencies generally have high transaction velocity. Therefore, they would require scalable, high throughput infrastructure provided by multi-asset blockchains. Currencies with lower transaction velocity (e.g. local currencies) could use multi-asset blockchains, colored coin protocols, or metacoins.

### Business to Consumer Assets
Digital assets could be used to represent discounts, coupons, vouchers, gift cards, loyalty points, etc. The assets would be issued by a merchant and transferred to buyers during purchases; the merchant would define a transparent set of rules of how assets can be redeemed for goods. A large retailer could issue multiple types of tokens and track their distribution and ownership, which would be useful for analyzing the customer base. Compared to existing implementations, blockchain infrastructure would provide a built-in secondary market for assets (although asset transfer could be restricted with the help of issuance metadata).

### Digital Subscription
Digital assets could be used to monetize access to digital resources, such as stream content.
Because of the transparency of blockchains, the content provider could easily check when the
user’s token was issued and whether it is still valid. The provider could issue multiple types of tokens that correspond to various levels of access (read/write or read-only), or access to specific resources or types of resources. Similar to digital subscription, non-transferable digital assets could be useful for role-based authentication.

### Digital Democracy
Digital asset coins can be used to implement voting by sending tokens to one of several designated addresses. While the existing digital asset systems are not secure enough to hold government elections, they can be used for voting among shareholders or in contests; in the latter case, a voting process is easily monetized. Permissionless or loosely regulated permissioned blockchains are expected to play a significant role in emerging IoT and consumer-to-consumer markets. Multi-asset blockchain and smart contract blockchains come as a viable alternative for business to consumer and consumer-to-consumer digital asset issuance.

A permissionless blockchain is suitable for on chain assets (virtual bearer assets) whereas in a permissioned permission less blockchain, a bearer asset becomes a registered asset and blockchain maintainers have a greater transparency and control on assets transfer across users compared to a permission less blockchain. A permissioned blockchain is more suitable for off- chain assets (e.g. fiat, securities, or titles).