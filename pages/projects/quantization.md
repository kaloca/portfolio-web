---
title: SigLIP on Jetson: Real-Time Edge Inference
date: 2026/3/1
description: INT8 quantization of an 800M vision model down to 63ms per frame
tag: ml
author: You
---

An 800M-parameter SigLIP vision encoder needed to run in real time on a Jetson Orin Nano for an on-device security application. Out of the box it was nowhere near fast enough.
The final configuration reached 63ms per frame (15.8 FPS) through INT8 quantization with NVIDIA ModelOpt, TensorRT engine compilation, and unlocking the Orin's Super power mode via nvpmodel. Along the way I debugged a kernel regression in the NvMap allocator (CVE-2025-33182) that capped pinned memory allocations, resolved with a targeted kernel module swap rather than a full downgrade.
The project was a good reminder that edge ML is half model optimization, half systems work.