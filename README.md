# CODESOFT-TASK-1
---
# 🤖 AI Chatbot with Rule-Based Responses

This project is a **Rule-Based Chatbot** developed using the **NLTK (Natural Language Toolkit)** library. It matches user inputs with predefined patterns using **regular expressions (RegEx)** and responds intelligently using the `Chat` utility from NLTK.

---

## 📌 Project Overview

This chatbot is built as **Task 1** for the **CodSoft Artificial Intelligence Internship**. It demonstrates basic **Natural Language Processing (NLP)** concepts like:

- Tokenization
- Pattern Matching with Regular Expressions
- Response Generation
- Pronoun Reflections

---

## 🚀 Features

- Understands greetings (hi, hello, hey)
- Responds to name introductions ("My name is...")
- Tells a joke 😄
- Responds to common queries like "How are you?"
- Handles unknown queries politely
- Ends conversation on "exit" or "bye"

---

## 🧰 Technologies Used

- 🐍 Python 3
  
- 🧠 [NLTK](https://www.nltk.org/) (Natural Language Toolkit)
  
- 🔍 Regular Expressions (`re`)
  
- `Chat` and `reflections` from `nltk.chat.util`

---

## 📦 Setup Instructions

1. 📥 **Install NLTK**
   
   Run this in your terminal or Jupyter/Colab:
   ```
   pip install nltk
      ```

2. 📚 Import Required Libraries

      ```
   import nltk
   import re
   from nltk.chat.util import Chat, reflections
   ```

3. 📥 Download NLTK Data
   
   You must download:

      ```
   nltk.download('punkt')
   nltk.download('averaged_perceptron_tagger')
   ```

4. 🧠 Define Patterns and Responses
   
      ```
      Patterns are written using regex and mapped to specific replies.
      ```

5. 🧱 Class & Function
      ```
      We define a chatbot class using Chat from NLTK, and a loop to handle interaction.
      ```

---

## 💬 Sample Interaction

<img width="855" height="400" alt="image" src="https://github.com/user-attachments/assets/791b329a-b99d-49c1-9a28-33483210ff74" />

