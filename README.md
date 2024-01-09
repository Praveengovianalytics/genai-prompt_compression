# Gen AI Prompt Compression

This README file provides an overview and setup guide for the `prompt_compression_workbook.ipynb`, a Jupyter notebook demonstrating prompt compression techniques for efficient LLM model interactions.

## Overview - Prompt Compression Workbook

The notebook showcases various techniques for compressing prompts, aimed at optimizing the use of Large Language Models (LLMs) like GPT-3.5 and GPT-4. It demonstrates how to compress prompts effectively, reducing the cost and computational requirements without significant loss in performance.

## Notebook Location

The original file is located at:
[Colab Notebook](https://colab.research.google.com/gist/Praveengovianalytics/217dee7ffc1d6b41d5ef3f0e2f34b79a/prompt_compression_workbook.ipynb)

## Setup and Dependencies

Install the necessary Python libraries:

```bash
!pip install openai -q
!pip install llmlingua -q
!pip install accelerate -q
!pip install llama_index -q
!pip install optimum auto-gptq -q
```

## API Key Configuration

Set up the OpenAI client with your API key:

```python
from openai import OpenAI
client = OpenAI(api_key = 'YOUR_API_KEY')
```

Replace `'YOUR_API_KEY'` with your actual OpenAI API key.

## Sample Prompts and Compression

The notebook includes examples of using GPT models to generate responses and compress prompts using LLMLingua:

1. **Example with GPT-3.5 Turbo:** Creating a poem explaining the concept of recursion.
2. **Using LLMLingua for Prompt Compression:** Demonstrates the use of LLMLingua to compress prompts and analyze the compression ratio.

## LLMLingua in Action

Details the process of setting up and using LLMLingua for effective prompt compression. This includes:

- Installing dependencies.
- Preparing prompts for ChatGPT 4 Preview.
- Compressing prompts with LLMLingua.
- Sending compressed prompts to GPT-4 for completion.

## Resetting the Session

Instructions for resetting the session and starting afresh with a new dataset are provided.

## Usage

Follow the steps in the notebook to experiment with different prompt compression techniques and observe their effects on LLM performance and efficiency.

---

**Note:** Ensure you have the necessary API keys and access rights to use the OpenAI and other relevant services demonstrated in the notebook.
