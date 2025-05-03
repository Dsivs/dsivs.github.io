+++
title = "Distributed Vector Database"
date = 2025-05-01 07:07:07+01:00
draft = false
slug = ""
comments = true
showpagemeta = false
showReadingTime = false
+++



---





<div style="text-align: center;">
  <img src="/img/DB.png" alt="The workflow of my database" style="max-width: 80%; height: auto;">
</div>




Designed and implemented a **distributed vector database** to efficiently store, index, and retrieve high-dimensional vectors across multiple nodes. The system supports **parallel similarity search** using vector embeddings and ensures scalability and fault tolerance through a  **sharded architecture with replication** . Core features include:

* **RPC-based communication** using gRPC for efficient inter-node messaging.
* **Custom indexing layer** using **FAISS** (or HNSW, if applicable) for fast approximate nearest neighbor (ANN) search.
* **Consistent hashing** for data partitioning and load balancing.
* **Protobuf-based schema** for defining structured data and query interfaces.
* Integrated **metadata management** to track vector IDs, versions, and node assignments.
* Optimized for low-latency query responses and horizontal scalability.

This project demonstrates system design skills in  **distributed systems, high-performance computing, and vector search algorithms** , suitable for applications in recommendation systems, image retrieval, and NLP.
