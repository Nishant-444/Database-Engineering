# The Database Engineering Handbook

_Compiled from the Hussein Nasser Course_

## 🟢 Module 1: The Physics of Data

- **[Chapter 02: Internals & Storage](./02_Internals_and_Storage.md)**
  - _Key Concepts:_ Pages, Rows vs Columns, Heap Architecture.
- **[Chapter 04: B-Tree vs B+Tree](./04_BTree_vs_BPlusTree.md)**
  - _Key Concepts:_ Fan-out, Leaf Node Linking, Page Splits.
- **[Chapter 10: Pluggable Engines](./10_Pluggable_Engines.md)**
  - _Key Concepts:_ InnoDB vs RocksDB, LSM Trees.

## 🔵 Module 2: Access Patterns & Indexing

- **[Chapter 03: Indexing Strategies](./03_Indexing_Strategies.md)**
  - _Key Concepts:_ Index Only Scans, Bitmap Scans, The Planner.
- **[Chapter 11: Database Cursors](./11_Cursors.md)**
  - _Key Concepts:_ Client vs Server Cursors, Pagination Death Spirals.
- **[Chapter 12: NoSQL Architecture](./12_NoSQL_Architecture.md)**
  - _Key Concepts:_ CAP Theorem, Document Stores, Key-Value Limits.

## 🟠 Module 3: Transactions & Concurrency

- **[Chapter 01: ACID & Transactions](./01_ACID_and_Transactions.md)**
  - _Key Concepts:_ Atomicity, WAL, fsync.
- **[Chapter 07: Concurrency Control](./07_Concurrency_Control.md)**
  - _Key Concepts:_ 2PL, Deadlocks, Pessimistic vs Optimistic Locking.

## 🔴 Module 4: Scaling & Distributed Systems

- **[Chapter 05: Partitioning](./05_Partitioning.md)**
  - _Key Concepts:_ Pruning, Horizontal vs Vertical, Row Movement Cost.
- **[Chapter 06: Sharding](./06_Sharding.md)**
  - _Key Concepts:_ Consistent Hashing, The "No Join" Rule.
- **[Chapter 08: Replication](./08_Replication.md)**
  - _Key Concepts:_ Async vs Sync, Split Brain, Replication Lag.

## ⚫ Module 5: Production & Security

- **[Chapter 09: System Design Case Studies](./09_System_Design_Cases.md)**
  - _Key Concepts:_ URL Shortener, Twitter Fan-out.
- **[Chapter 13: Database Security](./13_Security.md)**
  - _Key Concepts:_ TLS Handshake, SQL Injection, Pooling.
- **[Chapter 14: Homomorphic Encryption](./14_Homomorphic_Encryption.md)**
  - _Key Concepts:_ Zero Trust Computing.
