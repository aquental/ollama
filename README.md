# ollama

Version
```Shell
ollama -v
```

Libraries
-[https://github.com/ollama/ollama-python](ollama-python)
-[https://github.com/ollama/ollama-js](ollama-js)

## Quickstart
To run and chat with Llama 2:
```Shell
ollama run llama2
```

Python
```Shell
pip install ollama
```
```Python
import ollama
response = ollama.chat(model='llama2', Messages=[
 {
	'role': 'user',
	'content':  'Why the sky is blue?',
 },
])
print(response['message']['content']))
```
