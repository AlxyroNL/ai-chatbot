
````markdown
# AI Chatbot

A simple AI chatbot in Python using OpenAI's GPT-3.5/4.  
The chatbot keeps the entire conversation context and runs directly in the terminal. Type `stop` to end the chat.

---

## Features

- 🗣️ Chat naturally with AI
- 💬 Maintains full conversation context
- ⚡ Terminal-based (no GUI required)
- 🔄 Easily extendable and customizable

---

## Requirements

- Python 3.8+
- [OpenAI API Key](https://platform.openai.com/account/api-keys)

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ai-chatbot.git
cd ai-chatbot
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Set your OpenAI API key as an environment variable:

**Linux / macOS:**

```bash
export OPENAI_API_KEY="your_api_key"
```

**Windows (PowerShell):**

```powershell
setx OPENAI_API_KEY "your_api_key"
```

---

## Usage

Run the chatbot:

```bash
python chatbot.py
```

Example:

```
🤖 Welcome to the AI Chatbot! Type 'stop' to exit.
You: Hello AI!
AI: Hi there! How can I assist you today?
You: Tell me a joke.
AI: Why did the computer go to therapy? Because it had too many bugs! 😄
```

Type `stop` to end the conversation.

---

## Customization

* You can change the model by modifying the `model` parameter in `chatbot.py`:

```python
response = openai.ChatCompletion.create(
    model="gpt-4",  # or "gpt-3.5-turbo"
    messages=conversation
)
```

* Extend functionality by adding logging, GUI, or web interface.

---

## License

MIT License

```

