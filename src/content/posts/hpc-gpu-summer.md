---
title: "This Summer: HPC and GPU Systems"
description: "Why I am spending the summer closer to performance, parallelism, and the hardware side of applied AI."
date: 2026-05-31
tags: ["hpc", "gpu", "systems"]
draft: false
---

This summer I am taking High Performance Computing and GPU Hardware/Software. It is a good combination for where my interests are heading: close enough to AI to matter, but low-level enough to make me think harder about performance, parallelism, and the systems underneath modern products.

HPC has me focused on how work is divided, where data moves, what has to synchronize, and what the machine is actually doing. Correctness is only the first layer. The more interesting question is whether a program uses the available resources well and how its behavior changes as the problem gets larger.

The GPU course adds the hardware side of that thinking. GPUs reward parallel structure, but they make vague assumptions expensive. Memory hierarchy, data access patterns, and workload shape all matter. A computation that sounds simple at the product level can be difficult to run efficiently if the underlying structure is wrong.

The connection back to applied AI is straightforward. Enterprise AI products still have operating constraints: latency, throughput, cost, data movement, reliability, and integration. If those constraints are ignored, adoption gets harder no matter how impressive the model is.

I am not taking these courses because every applied AI role requires kernel-level work. I am taking them because deeper systems knowledge improves judgment. It helps me ask better questions about architecture, performance, and what has to be true for an AI product to work outside a demo.
