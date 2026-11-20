---
layout: default
title: Improving LLM guidance for CUDA-Q
parent: Writing Samples
nav_order: 1
---
# Improving LLM guidance for CUDA-Q

CUDA-Q is NVIDIA's hybrid programming model for CPUs, GPUs and QPUs working together. I benchmarked how well LLMs handle CUDA-Q tasks, found the problem areas, and restructured its `llms.txt` around how an LLM actually uses the documentation, adding examples for common pitfalls. I then re-ran the benchmarks: the revised `llms.txt` cut errors per completed task in half, from 1.5 to 0.75.

- [Repo](https://github.com/tedprodromou/cudaq-docs)
- [Revised llms.txt](https://github.com/tedprodromou/cudaq-docs/blob/main/llms.txt)
- [Benchmark results](https://github.com/tedprodromou/cudaq-docs/blob/main/benchmark-results.md)
