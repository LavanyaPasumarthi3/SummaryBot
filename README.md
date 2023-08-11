# SummifyBot: Text Summarization Using GPT-3.5

Summify Bot is a Python application that utilizes the power of the GPT-3.5 language model developed by OpenAI to generate concise and coherent summaries of user-provided text. Whether you need to summarize reviews, regular text, cover letters, or any other form of content, Summify Bot is designed to assist you in creating meaningful and succinct summaries.

**Note:** Before you begin, make sure you have access to the OpenAI GPT-3.5 API. You will need to replace `"YOUR_API_KEY"` with your actual API key in the code.

## Features

- Summarize lengthy text into shorter, coherent summaries.
- Handles a variety of text types, including reviews, general content, cover letters, and more.
- Easily configurable and customizable according to your specific use case.
- User-friendly command-line interface.

## Usage

1. Open the `Main.ipynb` file and replace `"YOUR_API_KEY"` with your actual GPT-3.5 API key.

2. Run the python file

3. Follow the prompts to provide the input text that you want to summarize.

4. Summify Bot will process the input text using the GPT-3.5 model and generate a summary.

## Configuration

You can customize the behavior of Summify Bot by modifying the parameters in the `config.py` file:

- `API_KEY`: Replace this with your GPT-3.5 API key.
- `MAX_TOKENS`: Set the maximum number of tokens in the generated summary. Adjust this to control the length of the summary.
- `TEMPERATURE`: Adjust the temperature parameter to control the randomness of the generated output. Higher values make the output more random, while lower values make it more deterministic.

## Example



## Acknowledgments

This project relies on the OpenAI GPT-3.5 model and is inspired by the capabilities it offers for text summarization.

