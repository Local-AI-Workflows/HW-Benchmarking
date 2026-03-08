# Hardware Benchmarks

This repository contains GPU hardware benchmarks generated with [Ollama](https://ollama.com/) on different GPU's. They aim to provide a rough comparison of how different Graphic/AI Accelerators perform when running local LLM inference workloads with Ollama.

The goal was to compare inference performance across various GPU product segments (server/desktop) and generations (Pascal - Hopper) using multiple benchmark tasks and language models.


## Benchmarked Tasks

The benchmarks were used to measure performance across several common LLM workloads:

- **Token Generation** – raw token throughput
- **Text Generation** – typical prompt → response generation
- **Complex Reasoning** – multi-step reasoning tasks
- **Large Context Summarization** – summarizing prompts with large context windows


## Language Models Used

The following models were used for the benchmarks:

- **Mistral (3.3B)**
- **DeepSeek R1 (12B)**
