# Therapy Chatbot

A **multilingual therapy chatbot** that emotionally interacts with users, detects their mood, and responds with empathy.  
It supports **text + speech output**, works directly in **Google Colab**, and **requires no extra setup** beyond basic Python libraries.

---
## Supported Languages
The chatbot can chat and speak in multiple languages:

- English  
- Tamil  
- Hindi  
- Japanese  
- Korean  
- Malayalam  
- Kannada  
- Telugu  
- Spanish  
- French  
- German  
- Chinese  

---

## Supported Emotions
This chatbot detects and responds based on user emotions:

- Sad  
- Happy  
- Anxious  
- Flirty  
- Friendly  
- Love  
- Motivational  
- Joke  
- Suicidal  
- Angry  
- Confused  
- Grateful  
- Default (neutral)

---

## Features
- Emotion detection from text input  
- Auto language translation  
- Real-time text-to-speech responses  
- Multilingual support (via Google Translate + gTTS)  
- Conversation history and session summary  
- Safe responses for distress messages (e.g., suicidal intent)  
- Fully interactive continuous chat loop  
- Runs entirely inside Google Colab  

---

## How to Run

### Step 1: Copy and Paste the Code  
Paste the provided Python code into **Google Colab**.

### Step 2: Install Required Libraries  
```python
!pip install googletrans==4.0.0-rc1 gtts -q
