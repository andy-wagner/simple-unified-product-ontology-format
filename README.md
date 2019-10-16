# simple-unified-product-ontology-format
Draft of a simplified ontology format specially designed from a proudct search and retrieval perspective

This repository holds proposals and tools for crafting a simple unified product ontology format.


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
