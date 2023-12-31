Bitcoin Layer 2 Protocols Research
(Lightning network, Liquid network and Rootstock)
Table of Content

Overview of the Layer 2 Protocol
Working mechanism or principle
Key features, benefits and use cases
Strengths, weakness and challenges
Ecosystem and Network Activity
Future outlook
Sources

Overview Of The Bitcoin Layer 2 Protocols
Bitcoin layer-2s aim to scale the network, enhancing programmability in the No. 1 blockchain and unlocking new utilities. With an average block time of 10 mins, a throughput of 7 TPS, and a high transaction cost of 21 USD, as well as Bitcoin’s limited support for smart contracts, Bitcoin layer-2s bring more functionality to the Bitcoin network and, in return, enjoy the security and network effects of Bitcoin.

There are many ways to scale Bitcoin, from sidechains to state channels, rollups, and client-side validation. Each method has its unique approach and technicality. The Lightning Network is arguably the most popular Bitcoin layer 2 and a typical example of state channels, while Liquid Network and Rootstock are examples of sidechains.

Top Bitcoin Layer 2 protocols

Lightning network,
liquid network 
Rootstock

Lightning Network
Lightning network enables near-instant payments utilising Bitcoin’s native smart contract scripting language. It also allows low fees and reduces transaction confirmation times by processing transactions off-chain, avoiding global consensus and network congestion.

Lightning network utilises payment channels, which are off-chain networks running parallel to the main blockchain, aiming to create a channel between two parties involved in the transaction. Then, the channel interacts with the mainnet at opening or closing, and when the channel is closed down, the latest state is bundled into a single transaction and submitted to the mainnet.


Working Mechanism Or Principle

Firstly, the Lightning network utilises a network of nodes that transact privately with each other via channels without requiring global consensus. It uses a bidirectional payment channel that involves two users sending and receiving Bitcoins without constantly broadcasting the transactions to the main blockchain.

Suppose two parties, A and B, wish to transact; they open a payment channel by depositing Bitcoin into a 2-of-2 multi-signature (multi-sig) wallet to open an on-chain funding transaction recorded on the mainnet. Similarly, channel closing is also done on-chain.

A and B can now transact off-chain and send funds to each other, and they will both sign every transaction with the channel balance updated each time a transaction is made. Afterwards, both parties can agree to close the transaction, and the funds are sent to their wallets, while the balance represented as a single transaction is broadcast to the Mainnet.

The lightning network also uses Hashed Timelock contracts (HTLC) to conduct secure transfers via many channels and across multiple hops to the final destination, unlike a bidirectional payment, which allows transfers within a channel.
Key Features, Benefits And Use Cases

Benefits
High throughput and fast transactions 
Lower fees
No third-party trust


Use Cases

Cross-chain Transactions
Lightning network transactions can be routed over multiple chains with different consensus mechanisms, provided that they enforce similar hash functions across chains. The sender or receiver’s chain doesn't matter.

Micropayments
Unlike Bitcoin, lighting network can afford micropayments with cheap transaction fees, for example, payments which are less than a dollar or even a fraction of a cent

Key Features

Multi-signature addresses
Hashed Timelock Contracts (HTLCs)
Bidirectional Payment Channels

Strengths, Weakness and Challenges

Weaknesses

Risk Of Coin Theft
The Lightning Network require nodes and parties to be online to broadcast transactions. The problem is when the nodes go offline, private keys can be compromised and coins stolen. Also, if the transactions are not broadcasted in time or the event of data loss, the second party can steal funds.

The risk of coin theft can be mitigated by using a third party to send funds or having a third-party data storage service. Even if an intermediary node is used, limiting the amount of funds in the hot wallet is crucial.
Coin theft risk also holds sway if invalid time-locked transactions become valid due to insufficient time.  Therefore, participants should select timelocks with ample amount of time.

Spam From Forced Expiration
This spam can occur when a bad actor creates many channels and forces them all to expire at once, thereby overwhelming the block data capacity and causing mass spam on the blockchain network, leading to transaction delay until the locked-time transactions are invalid.

Challenges
Privacy is challenging for the lightning network since they rely on a custodial wallet, an aberration to the Bitcoin mantra, “not your key, not your coins. ” Additionally, it is difficult to run a lightning node, so LN relies on a custodial solution, which is easy to set up and use.

Another keynote issue with the Lightning network is the difficulty and time-consuming process of finding a well-funded node with a direct channel to the recipient, when a user wants to make a payment that exceeds their channel balance.

Other challenges include the costs of opening and closing a channel, which is an on-chain transaction, the risk of a node going offline and being unable to process transactions through the channels it's connected to, as well the risk of double spending, which can occur when a node is offline and hence does not provide the correct transaction state.

Ecosystem and Network Activity

Bitcoin Brokerage and Services firm River reported about 6.6 million transactions on the Lightning network in August 2023, a 1,212% increase from August 2021 despite a 44% drop in the price of Bitcoin. Gaming, social media tipping, and streaming were the primary use cases driving 27% of the growth. 

River also reported about 279k to 1.116 million monthly active Lightning users as of September 2023. About 179 companies across 28 categories are also participating in the lightning network. At the time of writing, Lightning Network’s TVL is $213.36m, according to Defillama.


Future outlook
Arguably the most popular Bitcoin layer 2, it scored a significant win when Binance adopted it. Coinbase has also proposed adopting the network. As we march towards global crypto Adoption, the Lighting network will have a pivotal role to play by enhancing Bitcoin’s efficiency and scalability.

The lightning network's future lies in onboarding many merchants and integrating LN into existing payment systems. The LN team is working to achieve this by building partnerships with payment processors and user-friendly point-of-sale systems.
