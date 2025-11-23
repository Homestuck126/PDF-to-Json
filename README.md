---

# PDF-to-JSON

A lightweight proof-of-concept pipeline for converting PDFs into structured JSON.

## Overview

This project demonstrates a simple end-to-end workflow:

* **Text Extraction:** Uses the open-source `python-doctr` library to convert PDF files into plain text.
* **LLM Parsing:** Feeds the extracted text into the [Qwen 2.5 7B-Instruct](https://huggingface.co/Qwen/Qwen2.5-7B-Instruct) model to transform unstructured text into a clean, user-defined JSON format.
* **Notebook Deployment:** Runs entirely inside Google Colab for easy experimentation and zero-setup usage.

## Colab Notebook

Try it here:
[https://colab.research.google.com/drive/1iI2XybFhQkAhkYo2HvX4rKQ8MyUaKVXG?usp=sharing](https://colab.research.google.com/drive/1iI2XybFhQkAhkYo2HvX4rKQ8MyUaKVXG?usp=sharing)

---

