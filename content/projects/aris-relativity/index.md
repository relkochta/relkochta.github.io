---
title: "Special relativistic ray tracing"
date: 2000-01-30
externalUrl: "aris-relativity/report.pdf"
summary: |
  I extended a path ray tracer to account for Einstein's [special theory of relativity](https://en.wikipedia.org/wiki/Special_relativity), which describes what happens when objects move close to the speed of light.
  The technique is loosely based on a [1990 paper](https://dl.acm.org/doi/10.1145/100348.100384); each object in the scene is given its own reference frame, and ray intersections are sorted according to their times in the _observer's_ reference frame at each ray bounce. As part of this project, my friend also accounted for the [Doppler effect](https://en.wikipedia.org/wiki/Doppler_effect).
tags: ["python", "graphics"]
# description: ""
_build:
  render: "false"
  list: "local"
---
