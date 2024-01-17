# LLAMA Index Course

source: https://banked.udemy.com/course/llamaindex/learn/lecture/39824104

## Goals

Basic: Understand Large Language Models.
Stretch: The goal is to understand indexing and Retrieval AUgmented Generation (RAG).

LLM's take text as input (the prompt). They transform it to set of tokens (characters and white space). The context window is the maximum number of tokens a model can handle at once. The temperature controls the randomness of the output.

## Use cases

- Chat bots
- Autonomous agents

## RAG

- Fine tuning a LLM on a corpus of documents
- Re-training the base model
- RAG which introduces new knowledge to the model using prompts

### RAG - How it works

It takes in data from sources (using data connectors) and transforms it into an index; most likely a vector index.
