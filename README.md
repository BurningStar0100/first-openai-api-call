# GPT-3.5 Turbo Chat Script

This Python script allows you to interact with OpenAI's `gpt-3.5-turbo` model by sending a prompt and receiving a response via the OpenAI API. It also displays the number of tokens used during the interaction.

## ✨ Features

- Sends a user message and a fixed system prompt to GPT-3.5 Turbo
- Receives a response from the assistant
- Displays the assistant’s reply and the total number of tokens used
- Keeps your API key secure using a `.env` file
- Supports error handling

---

## 🛠️ Setup & Installation

### ✅ 1. Clone this repository or copy the script files

```bash
git clone https://github.com/BurningStar0100/first-openai-api-call
```
---

### ✅ 2. Create and activate a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
---

### ✅ 3. Install Python & Dependencies

Ensure you have **Python 3.7+** installed. Then, install the required library:

```bash
pip install openai python-dotenv
```
---

### ✅ 4. Create a `.env` File

Create a `.env` file in the **same directory** as your script with the following contents:

OPENAI_API_KEY = your_api_key_here
