# Project Description
The AI Chat Log Summarizer is a Python-based project that processes text chat logs between a User and an AI. It extracts structured insights such as:

Number of messages by speaker

Frequently used keywords (excluding stopwords)

Simple conversation summary

This project demonstrates basic Natural Language Processing (NLP) techniques and offers an optional TF-IDF-based keyword extraction enhancement.

📂 Input Format
A plain .txt chat log structured like:
User: Hello!  
AI: Hi! How can I assist you today?  
User: Can you explain what machine learning is?  
AI: Certainly! Machine learning is a field of AI that allows systems to learn from data.  

# ✅ Features
✅ Chat log parsing (User vs. AI)
✅ Count total and per-speaker messages
✅ Extract top 5 keywords (excluding stopwords)
✅ Generate human-readable summary

# 🛠 Requirements
Python 3.7+
nltk
sklearn (for TF-IDF, optional)
os, re, collections, etc.
# ▶️ How to Run
Clone the repository:
git clone https://github.com/yourusername/ai-chat-log-summarizer.git
cd ai-chat-log-summarizer
