---
title: "Minimizer-space suffix array"
date: 2000-01-05
externalUrl: "https://github.com/cephi-sui/mssa"
summary: |
  My friend and I extended the traditional suffix-array string search data structure to work in the _minimizer space,_ searching for sequences of minimizer k-mers rather than directly searching for the target sequence.
  We wrote a prototype in Rust :crab: and implemented an acceleration technique based on _piecewise linear regression_ to shrink the binary search space at the start.
  \
  [Technical Report :book:](mssa/report.pdf)
tags: ["rust", "string algorithms"]
# description: ""
_build:
  render: "false"
  list: "local"
---
