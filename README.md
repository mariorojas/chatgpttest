# Test script for ChatGPT

**INSTALLATION COMMANDS**

```
git clone https://github.com/mariorojas/chatgpttest.git
cd chatgpttest/
python3 -m venv venv
. venv/bin/active
pip install -r requirements.txt
```

Make sure to get your [OpenAI API key](https://platform.openai.com/account/api-keys) and set it in **main.py**

```
openai.api_key = 'your-key'
```

To interact with ChatGPT, run the following:

```
python main.py
# output: {"choices": ...
```
