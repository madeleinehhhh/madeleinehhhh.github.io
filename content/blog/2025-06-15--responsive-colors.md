---
title: One line of CSS for responsive colors
description: This is a post on My Blog about agile frameworks.
date: 2025-06-15
tags: code snippet
---
The title is a little misleading, as it requires a couple pieces be in place, but, if you're using css custom properties ("variables", colloquially), to set your background color, it only takes one line of css to change the foreground to either black or white.

More to come by way of an explanation and more strategies, but here's the code as I'm using it now:

```
color: hsl(from var(--c) 157 54 calc(18 + round(nearest,calc(100 - l),100)));
```