# LLM-Token-Cost-and-Calculator

A lightweight Streamlit app to estimate and compare daily and monthly token‐based costs for Large Language Models (LLMs) across Google Gemini and OpenAI.

## 🚀 Features

- **Automatic token counting** via OpenAI’s `tiktoken` BPE encoder  
- **Manual entry mode** for total daily input/output tokens  
- **Task-specific ratios** (Summarization, Q&A, Text Generation, Chat) to estimate output tokens  
- **Side-by-side cost comparison** for any Gemini vs. OpenAI model tier  
- **“Show base model rates”** toggle to reveal \$ per 1 M-token pricing  
- **Monthly projection** assuming 22 working days
