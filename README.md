# LLM without Embeddings (Simple Wikipedia Experiment)

## Overview

This project explores a language modeling experiment using the **Simple English Wikipedia dataset**, but **without using a traditional embedding layer**.

Instead of relying on standard token embeddings, this notebook investigates alternative representations and token handling strategies while building a lightweight language model pipeline.

The goal is to better understand how embeddings influence model performance and architecture in transformer-style models.

---

## Dataset

Dataset used: **Simple English Wikipedia XML Dump**

The raw dataset contains Wikipedia articles stored in XML format.

Processing steps:

* XML parsing
* extracting article text
* cleaning and normalization
* preparing a training dataset

The dataset is truncated to a smaller size for experimentation.

---

## Project Workflow

The notebook follows these main steps:

1. **Extract Wikipedia text**

   * Parse XML dump
   * Extract article content

2. **Text Cleaning**

   * Remove non-ASCII characters
   * Normalize whitespace
   * Prepare training corpus

3. **Dataset Preparation**

   * Limit dataset size
   * Convert text into token sequences

4. **Model Architecture**

   * Lightweight transformer-style architecture
   * No explicit embedding layer
   * Alternative token representation

5. **Training / Inference**

   * Setup model pipeline
   * Generate text predictions

---

## Technologies Used

* Python
* PyTorch
* Transformers
* XML parsing
* Regex text cleaning

---

## Key Libraries

* torch
* transformers
* requests
* wikiextractor

---

## How to Run

Clone the repository:

```
git clone https://github.com/YOUR_USERNAME/simplewiki-llm-without-embeddings
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the notebook:

```
jupyter notebook LLM_without_embedding.ipynb
```

---

## Research Motivation

This experiment is part of a broader exploration of **efficient language model architectures using small datasets**.
The goal is to investigate alternative model structures that reduce computational requirements.

---

## Author

Sangeetha KV
PhD Mathematics | Machine Learning | Data Science
