---
layout: page
title: Hardware Trojan Detection
description: RTL-level trojan injection, constrained-random testbench, and side-channel detection
img:
importance: 4
category: digital
---

Designed and injected RTL-level hardware trojans in Verilog to model microarchitectural
vulnerabilities and study trigger conditions.

- Wrote a Verilog testbench instantiating clean and trojan ALU variants simultaneously;
  applied 70,000 cycles of fixed-seed constrained-random stimulus to detect functional divergence
- Developed Python-based side-channel detection pipeline using switching activity signatures
  to identify anomalous RTL behavior