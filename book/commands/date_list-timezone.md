---
title: date list-timezone
version: 0.69.1
usage: |
  List supported time zones.
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> date list-timezone ```

## Examples

Show timezone(s) that contains 'Shanghai'
```shell
> date list-timezone | where timezone =~ Shanghai
```
