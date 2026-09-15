# AI Builders Hackathon 2026 - AI Training

This repository contains the data, notebooks, and supporting resources used for
the AI Builders Hackathon 2026 training project.

## Embedding Model

The retrieval pipeline uses the following Sentence Transformers model:

`sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2`

| Setting | Value |
| --- | --- |
| Expected local model directory | `models/multilingual-minilm/` |
| Embedding dimension | 384 |
| Embedding normalization | Enabled |

## Local Setup

Model weights are intentionally excluded from this repository. Download the
embedding model and place it in `models/multilingual-minilm/` before running
the retrieval pipeline.

## Repository Contents

- `data/` - source data, processed datasets, benchmarks, and example outputs.
- `notebooks/` - exploratory, integration, financial-analysis, and data-processing notebooks.
- `.env.example` - example environment-variable configuration.
- `requirements.txt` - Python dependencies for the project.
