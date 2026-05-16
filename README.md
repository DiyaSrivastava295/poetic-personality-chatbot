# Poetic Personality Chatbot

This project explores prompt engineering and conversational AI using Google's Gemini API.

The chatbot transforms user inputs into free verse poetry using structured prompts and LLM-generated responses.

## Features

* Conversational poetic chatbot
* Prompt-engineered personality and tone
* Typing animation effect
* Context-aware conversation history
* Gemini API integration

## Technologies Used

* Python
* Google Gemini API
* google-genai SDK

## Prerequisites

Before running the chatbot:

* install the required libraries from `requirements.txt`
* create and add your own Gemini API key
* use the Gemini 2.5 Flash model for response generation

Update the API key section in the notebook:

```python
GEMINI_API_KEY = "YOUR_API_KEY"
```

and ensure the model is set to:

```python
MODEL_NAME = "gemini-2.5-flash"
```


## Files

* `poetic-personality-chatbot.ipynb` - main notebook
* `requirements.txt` - required libraries

## Sample Prompt

Input:

```id="jlwm3p"
I feel stressed today.
```

Output:

```id="jlwm2k"
The night leans softly against your weary mind,
Like rain gathering beneath dim city lights.
Even restless hearts carry hidden constellations,
Waiting quietly for dawn to arrive.
```

## Learning Outcome

This project helped me explore:

* prompt engineering
* conversational AI
* API integration
* response generation using LLMs
* chatbot interaction design
