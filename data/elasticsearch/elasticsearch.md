# Elasticsearch

[Elasticsearch Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/dense-vector.html)

Elasticsearch is a search and analytics engine that supports hybrid search scenarios, including both full-text and vector similarity search, making it suitable for applications such as generative AI and retrieval augmented generation (RAG).

## Category
- Vector Database Engines

## Tags
- hybrid-search
- vector-search
- full-text-search
- open-source
- rag

## Features
- **Dense Vector Field Type**: Supports storing dense vectors (arrays of numeric values) for k-nearest neighbor (kNN) search.
- **kNN Search**: Efficient approximate kNN retrieval using the HNSW algorithm.
- **Similarity Metrics**: Supports various similarity metrics for vector search including cosine, dot_product, l2_norm, and max_inner_product.
- **Vector Quantization**: Reduces memory footprint using int8 (4x), int4 (8x), or bbq (32x, technical preview) quantization strategies for vector storage.
- **Bit Vectors**: Supports bit vectors for very high-dimensional data, using efficient storage and Hamming distance for similarity.
- **Indexing Options**:
  - Multiple kNN indexing algorithms: hnsw, int8_hnsw, int4_hnsw, bbq_hnsw (preview), flat, int8_flat, int4_flat, bbq_flat (preview).
  - Adjustable parameters for indexing, such as number of neighbors (m), ef_construction, and confidence interval for quantization.
- **Flexible Field Configuration**: Set element type (float, byte, bit), dimensionality (up to 4096), similarity metric, and whether to index the field for kNN search.
- **Update Indexing Strategy**: Supports updating the kNN indexing algorithm for dense vector fields via the Update Mapping API (with some restrictions).
- **Hybrid Search**: Enables combining full-text search and vector similarity search in a single query.
- **Script Score Queries**: Use custom scripts to rank documents by similarity to a query vector.
- **Dynamic Mapping**: Unmapped arrays of floats (128-4096 elements) are dynamically mapped as dense_vector fields.
- **Synthetic Source Support**: Dense vector fields support synthetic _source (generally available for TSDB indices, technical preview for others).

## Pricing
- Pricing information is **not provided** in the available content. Please refer to the [official pricing page](https://www.elastic.co/pricing/) for details.
