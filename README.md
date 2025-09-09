# ⚽ Football-chatbot-Fine-Tuning

A **football trivia question-answering chatbot** built using **Flan-T5-base** and fine-tuned with **LoRA (Low-Rank Adaptation)**.  
The model can answer football-related questions with a few-shot prompt-based approach and is deployed via **Streamlit** with **ngrok** for online access.

---

## 🔹 Project Overview

This project leverages the **HuggingFace Transformers** library and a trivia dataset to create a lightweight, specialized Q&A model. Key features include:

- **Data Cleaning & Preprocessing:** Removes noise, stopwords, and tokenizes questions and answers.
- **Exploratory Data Analysis (EDA):** Visualizes question/answer lengths and most common words using histograms and word clouds.
- **Fine-Tuning:** Uses **LoRA** to adapt the pre-trained Flan-T5-base model efficiently, reducing GPU memory usage.
- **Inference:** Few-shot prompt-based answering for football trivia.
- **Web App:** Interactive chatbot via Streamlit.
- **Deployment:** Accessible online using **ngrok**.

---

## 🔹 Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/Football-chatbot-Fine-Tuning.git
cd Football-chatbot-Fine-Tuning
pip install -r requirements.txt
