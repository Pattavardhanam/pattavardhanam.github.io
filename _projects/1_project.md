---
layout: page
title: CMOS Current Mirror
description: Full analog design flow on SKY130A — schematic to post-layout verification
img:
importance: 1
category: vlsi
---

Designed and verified a CMOS current mirror on the SKY130A PDK on Linux, completing the
full open-source analog design flow end-to-end.

- Designed schematic and analyzed performance through transient, corner, and Monte Carlo simulations
- Completed full flow: schematic → layout → GDS generation → DRC → LVS → post-layout verification
- Performed parasitic extraction and analyzed pre- vs. post-layout behavioral deviations
- Automated GDS, DRC, and LVS checks using GitHub Actions CI

Check out the [project website](https://pattavardhanam.github.io/lelo_ex_sky130a/)
