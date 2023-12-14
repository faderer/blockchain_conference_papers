## Scalability
### SlimChain (VLDB 2021)
A novel stateless blockchain system for scalable transaction processing with smart contract capabilities.
propose new off-chain smart contract execution, statelesson-chain transaction validation, and novel state commitment schemes to realize SlimChain in both permissionless and permissioned settings.

### Qanaat: A Scalable Multi-Enterprise Permissioned Blockchain System with Confidentiality Guarantees (VLDB 2022)
A scalable multi-enterprise permissioned blockchain system that guarantees confidentiality.
present an infrastructure consisting of ordering nodes, execution nodes, and a privacy firewall and a data model consisting of data collections to preserve confidentiality.

## Efficiency
### A Transactional Perspective on Execute-order-validate Blockchains (SIGMOD 2020)
propose a novel method to enhance the execute-order-validate architecture, by reordering transactions to reduce the abort rate.

### NeuChain: A Fast Permissioned Blockchain System with Deterministic Ordering (VLDB 2022)
introduce the deterministic ordering technique to blockchain and propose the EV architecture. This design brings the flexibility in ordering intra-block transactions and further reduces the number of transaction conflicts through transaction reordering.

### ParBlockchain: Leveraging Transaction Parallelism in Permissioned Blockchain Systems
an order-execute paradigm for permissioned blockchains.
support distributed applications processing workloads with some degree of contention.

### Bidl: A High-throughput, Low-latency Permissioned Blockchain Framework for Datacenter Networks (SOSP 2021)
the first permissioned blockchain framework highly optimized for datacenter networks. 
leverage the network ordering in such networks to create a shepherded parallel workflow, which carries a sequencer to parallelize the consensus protocol and transaction execution speculatively.


## Sharding
### Towards Scaling Blockchain Systems via Sharding (SIGMOD 2019)
the first to present a sharded permissioned blockchain that supports workloads beyond cryptocurrency and scales scale to few thousands of transactions per second.
improve the efficiency and security with cross-shard functionality.

### SharPer: Sharding Permissioned Blockchains Over Network Clusters (SIGMOD 2021)
SharPer, a permissioned blockchain system that supports the concurrent processing of transactions by clustering nodes into clusters and sharding both data and the ledger.

## Distributed Database
### Blurring the Lines between Blockchains and Database Systems: the Case of Hyperledger Fabric (SIGMOD 2019)
first explore Fabric from the perspective of database research, where they observe weaknesses in the transaction pipeline.
solve these issues by transitioning well-understood database concepts to Fabric, namely transaction reordering as well as early transaction abort.

### Blockchains vs. Distributed Databases: Dichotomy and Fusion (SIGMOD 2021)
We compare blockchains and distributed databases as two different types of distributed, transactional systems. We propose a new taxonomy that characterizes both types of systems and their hybrids along four design dimensions: replication, concurrency, storage, and sharding.

## Interoperability
### Leveraging Public-Private Blockchain Interoperability for Closed Consortium Interfacing (INFOCOM 2021)
first attempt to address the issue of communication of consumer requests, and processed responses between a private blockchain based consortium and the open network through public-private blockchain interoperability.