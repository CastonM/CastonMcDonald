---
title: "My Georgia Tech MSCS So Far"
description: "A high-level look at the systems coursework and projects that have shaped how I think about software."
date: 2026-05-31
tags: ["georgia-tech", "systems", "omscs"]
draft: false
---

I started Georgia Tech's MSCS because I wanted to become more technical in a serious way. Consulting gave me a strong base in strategy, product, requirements, and delivery, but I wanted a deeper understanding of the systems underneath the products I was helping shape.

The systems courses have been the most useful lens for me. In Graduate Introduction to Operating Systems, the projects covered sockets, multithreaded clients and servers, inter-process communication, shared memory, caching, and distributed file-system patterns. The work made me more precise about boundaries: what a protocol guarantees, how concurrency changes behavior, and why a clean interface matters.

Advanced Operating Systems pushed that further into virtualization, synchronization, distributed services, and parallel execution. Projects around virtual CPU scheduling and memory coordination made resource management feel concrete. Other work touched MPI/OpenMP barriers, distributed services, and MapReduce-style computation. The common thread was coordination: independent parts of a system need structure if they are going to move together.

Computer Networks and related coursework added topology and control-plane thinking. Projects around routing, spanning trees, distance vector behavior, software-defined networking, and network function virtualization made me think more carefully about paths, policies, orchestration, and failure.

Across the program, the biggest shift has been judgment. I am better at asking where the bottleneck is, what has to synchronize, what can fail independently, and what tradeoffs a system is hiding. That carries directly into applied AI work, where the model is only one part of a larger product, workflow, and infrastructure system.
