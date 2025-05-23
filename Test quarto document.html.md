---
title: "Test quarto document with Git"
author: "Cory Holdom"
format: html
keep-md: true
editor: visual
---




## Quarto

Quarto enables you to weave together content and executable code into a finished document. To learn more about Quarto see <https://quarto.org>.

## Running Code

When you click the **Render** button a document will be generated that includes both content and the output of embedded code. You can embed code like this:



::: {.cell}

```{.r .cell-code}
1 + 1
```

::: {.cell-output .cell-output-stdout}

```
[1] 2
```


:::
:::



You can add options to executable code like this



::: {.cell}
::: {.cell-output .cell-output-stdout}

```
[1] 4
```


:::
:::



The `echo: false` option disables the printing of code (only output is displayed).
