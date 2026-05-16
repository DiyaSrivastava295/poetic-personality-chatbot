Here is the streamlined version with the emojis removed, a shorter introduction, and the setup and customization sections kept intact.

---

# LYRA: Poetic Personality Chatbot

LYRA is a conversational AI script built using Colab and the Google Gemini API. Powered by the `gemini-2.5-flash` model, LYRA responds to all user inputs exclusively in 4-6 line emotional, lyrical free-verse poetry.

## Features

* **Poetic Persona**
* **Context Awareness:** Remembers the last 10 conversation turns for personalized responses.
* **Immersive Output:** Custom typing effect.
* **Interactive Loop & Demo:** Includes an interactive chat loop and test sequence.

## Prerequisites

* **Python 3.7+**
* A valid **Google Gemini API Key** 

## Installation & Setup

1. **Install the required library:**
Install the official Google GenAI SDK via pip:
```bash
pip install google-genai

```


2. **Add your API Key:**
Open `poetic_personality_chatbot.py` in your text editor. Find the following line near the top of the file:
```python
GEMINI_API_KEY = "YOUR_API_KEY"

```


Replace `"YOUR_API_KEY"` with your actual Gemini API key.

## Usage

* **Chatting:** Type your message and press `Enter`. Wait a moment as LYRA generates and types out a customized poem.
* **Exiting:** To end the chat and receive a farewell poem, type: `quit`, `exit`, `bye`, `goodbye`, `farewell`, or `stop`.
* **Demo Mode:** After you exit the chat loop, the script will automatically run a brief demonstration using pre-written inputs to showcase its memory.

## Customization

You can easily tweak the chatbot's personality or behavior by modifying variables within the script:

* **`SYSTEM_PROMPT`**: Change the rules, themes, or line counts to make LYRA write in different styles.
* **`MAX_HISTORY_TURNS`**: Change the integer value (currently `10`) to increase or decrease the chatbot's memory span.
