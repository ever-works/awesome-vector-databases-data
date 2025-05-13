# Apache Cassandra

[Apache Cassandra](https://cwiki.apache.org/confluence/display/CASSANDRA/CEP-30:+Approximate+Nearest+Neighbor(ANN)+Vector+Search+via+Storage-Attached+Indexes) is a NoSQL database engine that now supports high-dimensional vector storage and approximate nearest neighbor (ANN) search. The recent enhancements enable Cassandra to be used for vector search workloads in addition to its core NoSQL capabilities.

## Features
- **Native Vector Search**: Supports storage and retrieval of high-dimensional vectors, enabling use cases such as similarity search and AI-driven applications.
- **Approximate Nearest Neighbor (ANN) Search**: Implements ANN search for vectors using the HNSW (Hierarchical Navigable Small World) algorithm. The HNSW implementation is based on Lucene, allowing for efficient and scalable ANN queries.
- **Storage Attached Indexes (SAI) Integration**: Extends the existing SAI framework to support vector indexing via a new `ann_index` scheme. This modularity allows for future extensibility in indexing approaches.
- **New Data Type and Query Operators**: Introduces a new VECTOR data type and ANN-specific query operators in CQL (Cassandra Query Language), enabling seamless integration of vector search in Cassandra queries.
- **Cosine Similarity**: Uses cosine similarity as the metric for measuring vector similarity in ANN searches.
- **Backward Compatibility**: The new features are designed to maintain compatibility with existing Cassandra installations and workflows.
- **Open Source**: The features are available as part of the open-source Cassandra 5.0 release.

## Category
- Vector Database Engines

## Tags
- nosql
- vector-search
- ann
- open-source

## Pricing
Apache Cassandra is open source and free to use under the Apache License.