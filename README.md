# 🧠 OpenAI Fine-Tuning with BBC News Dataset

Fine-tuning a pre-trained OpenAI model to classify news articles into categories like **Business**, **Tech**, **Politics**, **Sport**, and **Entertainment**.

This project demonstrates the complete fine-tuning workflow — from dataset preparation to model evaluation — using the [BBC News dataset](https://huggingface.co/datasets/Kessel/bbcnews).

---

## 📘 Overview

Large Language Models (LLMs) are powerful, but they’re often too general for domain-specific tasks.  
Fine-tuning bridges that gap — allowing you to train models on your **own data** to perform better on tasks like:

- Content classification  
- Sentiment analysis  
- Text summarization  
- Customer support chatbots  

This project shows how to fine-tune `gpt-3.5-turbo` using OpenAI’s fine-tuning API.

---


### Pre-requisites:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/mandeep111/openai-fine-tuning.git
cd openai-fine-tuning
```

### 2️⃣ Create and Activate Virtual Environment
```bash
python3 -m venv fine_tuning
source fine_tuning/bin/activate
```

### 3️⃣ Set Up Open API key
```bash
export OPENAI_API_KEY="your_api_key_here"
```
