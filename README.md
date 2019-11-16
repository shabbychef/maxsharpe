

# Conditional inference on the asset with maximum Sharpe ratio

[![Build Status](https://travis-ci.org/shabbychef/maxsharpe.svg?branch=master)](https://travis-ci.org/shabbychef/maxsharpe)

This repository contains the `knitr` source code to generate the
paper, ['Conditional inference on the asset with maximum Sharpe ratio'](https://arxiv.org/abs/1906.00573).

## This document

The document itself is written in `knitr`. You should be able to run the code
and build the document via `make` as follows:


```bash
make help
# knit the code; could take a while
touch maxsharpe.Rnw
make maxsharpe.tex
# build the document
make maxsharpe.pdf
```

You can also generate all the R code as follows:

```bash
make maxsharpe.R
```

<!-- modelines -->
<!-- vim:ts=2:sw=2:tw=96:fdm=marker:syn=markdown:ft=markdown:ai:nocin:nu:fo=ncroqlt:cms=<!--%s-->
