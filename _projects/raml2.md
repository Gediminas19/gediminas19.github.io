---
layout: page
title: Resource Aware ML 2
description: A Modern Implementation of Automatic Amortized Resource Analysis
img: assets/img/raml2.jpg
importance: 1
category: research
related_publications: false
---

### Collaborators
- [Jan Hoffmann](https://www.cs.cmu.edu/~janh/)

### Languages Involved
- Implementation: OCaml
- Source: SML, OCaml

### Overview
- Designed and implemented a new Intermediate Representation (RaML IR) that leverages de-Bruijn indices
- Engineered frontend to parse, filter, and translate SML code into the RaML IR
- Augmented and implemented a new resource analysis type system by [Grosen et al](https://www.cs.cmu.edu/~janh/assets/pdf/GrosenKH23.tr.pdf) that can analyze programs containing regular recursive types
- Wrote my [MS thesis](/assets/pdf/raml-thesis.pdf) on my implementation and results, published in the CMU SCS Technical Report Collection
- Designed and implemented a new resource analysis type system that can analyze programs containing exception and effect handlers, submission under review
