---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# My simple notebook

Some heel veel text, heel veel text, heel veel text, heel veel text,heel veel text,heel veel text

```{code-cell} ipython3
:tags: [mytag]

from myst_nb import glue
from IPython.lib.display import YouTubeVideo
video = YouTubeVideo('b_pTxGu2L04')

glue("vid", video)

```

## A section
<div style='text-align: center;'> 

A center aligned header 2 

```{glue:} vid
```
</div>

<div style='text-align: right;'> 

A right aligned header 2 

```{glue:} vid
```
</div>
And some more Markdown...

```{glue:figure} boot_fig
:figwidth: 300px
:name: "fig-boot"

This is a **caption**, with an embedded `{glue:text}` element: {glue:text}`boot_mean:.2f`!
```

