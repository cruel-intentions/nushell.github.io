---
title: or
version: 0.69.1
usage: |
  Includes an OR clause for an expression
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> or (or)```

## Parameters

 -  `or`: OR expression

## Examples

Creates an AND expression
```shell
> (field a) > 1 | or ((field a) < 10) | into nu
```
