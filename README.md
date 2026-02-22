# MLLM-2 — Micro Local Language Model 2

MLLM-2 is a lightweight probabilistic language model designed for fast text prediction, autocomplete systems, and educational experimentation.

Unlike neural language models, MLLM-2 relies on multi-order n-gram statistics rather than deep learning. This makes it fast, interpretable, and easy to run on ordinary hardware.

---

## Model Variants

This repository includes three versions so you can choose the one that fits your needs.

### MLLM-2-READY

A starter version with no corpus included.

Use this if you want to train the model on your own data or integrate it directly into an application as a customizable prediction engine.

### MLLM-2-Mini

A compact 74 KB version.

Suitable for small projects, embedded tools, demonstrations, and educational purposes where size and speed matter more than prediction depth.

### MLLM-2-Large

A fuller 747 KB version.

Provides improved prediction quality and richer output due to a larger built-in corpus and statistical base.

---

## Try It Online

You can test MLLM-2 in your browser:

https://sites.google.com/view/mllm-2/chat

No installation is required.

---

## How It Works

MLLM-2 builds multiple statistical language models simultaneously, ranging from single-word frequency models to longer phrase models of up to 20 tokens.

During prediction, the system:

1. Searches for the longest matching sequence in the current context
2. Falls back to shorter sequences when necessary
3. Selects the next token probabilistically based on observed frequency

This produces a lightweight yet practical text prediction engine.

---

## Use Cases

MLLM-2 is well suited for:

* Autocomplete and predictive typing systems
* Offline or low-resource AI tools
* Educational demonstrations of language modeling
* Embedded or experimental NLP projects
* Applications where transparency and speed are more important than neural-level fluency

---

## Getting Started

1. Clone the repository
2. Open the Python file
3. Add or modify the corpus if desired
4. Train the model
5. Run the interactive interface

The project depends only on standard Python libraries.

---

## Purpose

MLLM-2 is intended to demonstrate that useful language prediction can be achieved with simple statistical methods. It provides a transparent alternative to neural models and a practical foundation for experimentation, learning, and lightweight deployment.
