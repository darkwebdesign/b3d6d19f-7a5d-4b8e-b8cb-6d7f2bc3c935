---
layout: default
title: Welcome
nav_order: 1
redirect_from:
  - /docs/5.1/
---

# Symfony Add-on Pack

Symfony Add-on Pack is a collection of extra Symfony components that you can use in your Symfony applications.

## Features

### Data Transformers

* BooleanToValueTransformer, transforms between a boolean and a scalar value.
* EntityToIdentifierTransformer, transforms between an identifier and a Doctrine entity.

### Form Field Types

* BirthdayType, handles birthday data.
* BooleanType, transforms an user selected value into a boolean.
* EntityType, transforms an user entered identifier into a Doctrine entity.
* UnstructuredType, handles unstructured data.

### Validation Constraints

* Bsn, validates that a value is a valid Dutch social security number (BSN).
* Collection, validates that every item in a collection validates against one or more constraints.
* Json, validates that a value is valid JSON.

## License

Symfony Add-on Pack is licensed under the MIT License - see the `LICENSE` file for details.
