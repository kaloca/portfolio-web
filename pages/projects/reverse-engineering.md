---
title: AI-Assisted Reverse Engineering
date: 2026/02/01
description: Building AI agents for automated binary analysis
tag: ai
author: Gabriel
---

# AI-Assisted Reverse Engineering

Famously only one person in the world is publicly known to be able to bypass Denuvo (EMPRESS). Reading a bit on what it takes, watching the Voksi tutorial and reading [this](https://t.co/DLf6g5nv0n) article on a recent attempt in cracking Hogwarts Legacy, I started wondering if agents could help automate this repetitive work.

The biggest bottleneck is that agents have no easy way of using tools like Ghidra and x64dbg: their GUIs are generally much more usable than their CLI versions. That's what I'm attempting to fix first.

## Areas of Exploration

- Automated deobfuscation
- Control flow recovery
- Patch generation

Ongoing project (2025 - Current).
