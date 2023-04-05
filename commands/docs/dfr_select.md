---
title: dfr select
categories: |
  lazyframe
version: 0.78.0
lazyframe: |
  Selects columns from lazyframe.
usage: |
  Selects columns from lazyframe.
---

# <code>{{ $frontmatter.title }}</code> for lazyframe

<div class='command-title'>{{ $frontmatter.lazyframe }}</div>

## Signature

```> dfr select ```

## Examples

Select a column from the dataframe
```shell
> [[a b]; [6 2] [4 2] [2 2]] | dfr into-df | dfr select a
╭───┬───╮
│ # │ a │
├───┼───┤
│ 0 │ 6 │
│ 1 │ 4 │
│ 2 │ 2 │
╰───┴───╯

```