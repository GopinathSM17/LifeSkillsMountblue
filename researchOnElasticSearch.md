# Research Title

A brief overview of different types of elastic search, such as Elasticsearch, Solr and Lucene.

## Elasticsearch

1. **Fundamentally, Elasticsearch organizes data into documents, which are JSON-based units of information representing entities.
2. **Documents are grouped into indices, similar to databases, based on their characteristics. 
3. **Elasticsearch uses inverted indices, a data structure that maps words to their document locations for an efficient search.

## Solr

1. **The search query in solr is processed by a request handler.
2. **A request handler is a Solr plug-in that defines the logic to be used when Solr processes a request.
3. **To process a search query, a request handler calls a query parser, which interprets the terms and parameters of a query.

## Lucene

1. **Lucene uses an inverted index (mapping of a term to its metadata).
2. **The fundamental units of indexing in Lucene are the Document and Field classes.
3. **A Document is a container that contains one or more Fields.

## References

- https://solr.apache.org/guide/6_6/overview-of-searching-in-solr.html
- https://www.knowi.com/blog/what-is-elastic-search/
- https://medium.com/@karkum/introduction-to-apache-lucene-7d65f67f5231
