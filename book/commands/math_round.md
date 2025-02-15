---
title: math round
version: 0.69.1
usage: |
  Applies the round function to a list of numbers
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> math round --precision```

## Parameters

 -  `--precision {number}`: digits of precision

## Examples

Apply the round function to a list of numbers
```shell
> [1.5 2.3 -3.1] | math round
```

Apply the round function with precision specified
```shell
> [1.555 2.333 -3.111] | math round -p 2
```
