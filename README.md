# New Zealand IMF 2025 – LLM Data Analysis


## Project Overview

This project analyses New Zealand's 2025 IMF Country Report using Large Language Models (LLMs) in Google Colab. It extracts economic indicators, summarises report sections, identifies financial risks and presents the findings in a four-panel dashboard.

## Models Used

- **Qwen2.5-14B-Instruct:** Summarisation, financial extraction and RAG answers.
- **Mistral NeMo 12B:** Independent LLM evaluation.
- **all-mpnet-base-v2:** Text embeddings for FAISS retrieval.

## Tools and Libraries

Python, Google Colab (A100 GPU), PyMuPDF, Transformers, Sentence-Transformers, FAISS, Pandas and Matplotlib.

## Project Features

- PDF text extraction and token-aware chunking
- Eight section summaries and an executive summary
- Six economic indicators and seven financial themes
- Six economic strengths and six vulnerabilities
- Four economic trend series (2021–2030)
- FAISS-based Retrieval-Augmented Generation
- 18 LLM evaluations
- High-resolution four-panel dashboard

## How to Run

1. Open the notebook in Google Colab.
2. Enable an A100 GPU.
3. Run all cells sequentially.
4. Upload the New Zealand IMF 2025 PDF when prompted.
5. View the generated JSON, CSV and dashboard outputs.

