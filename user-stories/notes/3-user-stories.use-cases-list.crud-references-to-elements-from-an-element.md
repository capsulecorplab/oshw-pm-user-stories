---
id: lau1i8byyd5j5qfwub8ho4s
title: CRUD References to Elements from an Element
desc: ''
updated: 1738099051814
created: 1736890793225
---

## notes

- references should only be able to reference elements within the scope of the element that owns the reference (i.e., elements are unaware of parent or sibling elements; relationships between siblings are defined in a parent element)
- views reference elements
  - views are always siblings to elements
  - therefore, a view must be provided element(s) as input
  - elements that views are provided as input are provided via an interface into said view
- references are a 1-to-1 or 1-to-many relationship
