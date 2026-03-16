
# AI Research Assistant for Students

## Overview

This project develops a **prototype AI Research Assistant** using a **Large Language Model (LLM)** to help students quickly understand academic articles. The system can summarize long text, extract insights, answer questions, and generate concise explanations.

---

## Features

* Summarize long research articles
* Extract key insights from text
* Answer questions about the content
* Generate concise explanations

---

## Task 1 – LLM Interaction

* Used an LLM API (OpenAI / Gemini / HuggingFace).
* Sent a research article as input.
* Generated a summarized output using Python.

---

## Task 2 – Prompt Engineering

Three prompting techniques were tested:

**1. Zero-Shot Prompt**

* Model summarizes text without examples.

**2. Few-Shot Prompt**

* Provided example summaries before summarizing new text.

**3. Chain-of-Thought Prompt**

* Model analyzes the article step-by-step before generating a summary.

---

## Task 3 – Prompt Optimization

An improved prompt was designed to produce:

* **3 key insights**
* **1 actionable takeaway**
* **Professional executive summary**

Tested on two different research articles.

---

## Task 4 – Tokenization

Used a tokenizer (HuggingFace / tiktoken) to:

* Tokenize a paragraph
* Count total tokens
* Display tokenized output

---

## Task 5 – Mini AI Tool

Built a simple AI assistant that:

* Accepts article text as input
* Sends prompt to an LLM
* Generates:

  * Short summary
  * Key insights
  * One actionable recommendation

---

## Technologies Used

* Python
* LLM API (OpenAI / Gemini / HuggingFace)
* Transformers / Tokenizer
* Jupyter Notebook

---

## Conclusion

The AI Research Assistant demonstrates how **Large Language Models can help students quickly understand complex academic content** by summarizing articles and extracting meaningful insights.
