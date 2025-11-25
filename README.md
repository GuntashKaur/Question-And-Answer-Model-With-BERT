🎯 BERT Question Answering System (HuggingFace Transformers)
-

Welcome to this project showcasing how to build an intelligent Question Answering (QA) system using BERT Large Uncased Whole-Word-Masking Fine-Tuned on SQuAD!
This repository also includes a custom FAQ Bot powered by a fixed knowledge base about Sunset Motors, demonstrating domain-specific QA.

## 🔍 General QA Demo: DVD Release Example

The first part shows how BERT answers a simple question such as:

✨ “When was the first DVD released?”
By providing a passage, BERT identifies the correct start and end token positions, reconstructs the phrase, and returns the correct answer.
This demonstrates how extractive QA works step-by-step.

## 🤖 Custom FAQ Bot: Sunset Motors Dealership

A complete FAQ bot is built using a fixed context paragraph describing Sunset Motors, including:

🏬 dealership history

📍 location

🚗 vehicle brands

🌿 sustainability initiatives

📏 dealership size

💰 financing and services


The bot can answer questions such as:
“Where is the dealership located?”
“What brands of cars are available?”
“How large is the dealership?”


### 🧠 Concepts Included in This Project

This project covers a wide range of NLP concepts, including:

✨ Transformer-based Question Answering

✨ Tokenization and WordPiece embeddings

✨ Start and end logits for answer span prediction

✨ Input embeddings & attention mechanisms

✨ Context + question encoding

✨ Cleaning and reconstructing tokens

✨ Custom FAQ bot logic

✨ Using BERT without pipelines to understand internal workings


