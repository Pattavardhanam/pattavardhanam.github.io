---
layout: page
title: Hardware-Aware Spectrum Monitor
description: ISM band channel occupancy analyzer with jammer-like anomaly detection — CMOS role
img:
importance: 3
category: hardware
---

Passive, hardware-aware spectrum sensing platform for real-time channel occupancy analysis
and interference detection in the 865–867 MHz ISM band using LoRa, FPGA, and CMOS.

- Designed a transistor-level StrongARM latch comparator in Xschem/Ngspice achieving
  6–7 mV sensitivity and 10 ns decision time under low-amplitude, noise-dominated inputs
- Performed end-to-end validation across noise-only, signal-present, and jammer conditions,
  demonstrating correct channel occupancy detection and dual-threshold interference classification
- Analyzed metastability as a functional indicator, detection margins, and transition dynamics
  between uncertain and deterministic decision regions