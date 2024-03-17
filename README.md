# chatgpt-document-chatbot

Script to use ChatGPT on your own document files.

## Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip install langchain openai chromadb tiktoken unstructured
```
Modify `constants.py` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys).

Place your own data into `data/data.txt`.

## Example usage
Test reading `data/data.txt` file.
```
> python chatgpt.py "How is the culture in Dallas?"
The culture in Dallas is rich and diverse, offering a mix of art, entertainment, culinars has a lively culinary scene with a wide range of cuisines to explore, from Texas barbecue to upscale dining. Sports are also a big part of Dallas culture, with passionate fan bases for teams like the Dallas Cowboys, Dallas Mavericks, and Dallas Stars.
```

Test reading `data/series-notes.pdf` file.
```
> python chatgpt.py "Who leads the overall score between the Nuggest and the Mavericks?"
The Mavericks lead the all-time series against the Nuggets, with a record of 96-92 (.511).
```