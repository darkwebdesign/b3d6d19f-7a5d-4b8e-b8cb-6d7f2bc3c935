---
layout: default
title: Data transformers
nav_order: 3
has_children: true
toc: false
redirect_from:
  - /docs/latest/transformers
---

# Data transformers

You'll often find the need to transform the data the user entered in a form into something else for use in your program. You
could easily do this manually in your controller, but what if you want to use this specific form in different places?

This is where Data Transformers come into play.

## Supported Transformers

The following transformers are available:

### Scalar Transformers

* [BooleanToValueTransformer](boolean-to-value-transformer.md)

### Other Transformers

* [EntityToIdentifierTransformer](entity-to-identifier-transformer.md)
