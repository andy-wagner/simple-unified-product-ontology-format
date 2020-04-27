# simple-unified-product-ontology-format
Draft of a simplified ontology format specially designed from a product search and retrieval perspective

This repository holds proposals and tools for crafting a simple unified product ontology format.

## Fundamentals
An ontology is a formal explicit description of a domain by identifying classes (or concepts), slots and slot restrictions between classes for a particular domain.

Existing eCommerce ontologies are not really optimized for product search and retrieval.
Instead of using supply side ontologies or topic groupings like catalog side ontologies we should look for atomicity. Or in other words the most basic words, attributes or other markers that precisely describe a product or SKU.

Therefore products should be atomic, can have synonyms or hyponyms and can have parents and attributes

## Design goals

- human readable
- machine parsable standard format (JSON)


## Format proposal

A simple example could be:

```yaml
definitions:
- : domain 
  id: 436 
  labels: home
  - : product
    id: 443
    labels: chair
    synonyms:
      - seat, sitting
    producttypes:
      - armchair
      - chaise longue    
``` 
