# simple-unified-product-ontology-format
Draft of a simplified ontology format specially designed from a search and retrieval perspective

This repository holds proposals and tools for crafting a simple unified product ontology format.


## Design goals

- human readable
- machine parsable standard format (JSON)


## Format proposal

We strive for a format parsable and validatable using a standard tool. 
A simple example could be:

```yaml
definitions:
- : domain 
  id: 436 
  labels: furniture
  - : product
    id: 443
    labels: chair
    synonyms:
      - seat, sitting
    producttypes:
      - armchair
      - chaise longue    
``` 
