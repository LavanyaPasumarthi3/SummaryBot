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

## Snapshots

## Regular Text summary
![reg1](https://github.com/LavanyaPasumarthi3/SummaryBot/assets/141587110/cff86505-c20c-442a-b95a-04c81dac0dd5)
![reg2](https://github.com/LavanyaPasumarthi3/SummaryBot/assets/141587110/ab4ea2f0-e6d3-42c6-9b9b-5a4254f97dc4)

## Postive product review summary
![prod1](https://github.com/LavanyaPasumarthi3/SummaryBot/assets/141587110/1fa6bdb4-9b71-4ba4-8b4a-d370e209a5ad)
![prod2](https://github.com/LavanyaPasumarthi3/SummaryBot/assets/141587110/a4f603e9-b333-4bc0-91d9-8a6395888ac9)

## Negative product review summary
![prod3](https://github.com/LavanyaPasumarthi3/SummaryBot/assets/141587110/c50c3662-39f7-48bb-bfcb-b5e83ac03f6c)
![prod4](https://github.com/LavanyaPasumarthi3/SummaryBot/assets/141587110/a460f167-e8a7-4af4-a4a9-56770afe2051)

## Cover Letter Summary
![sum1](https://github.com/LavanyaPasumarthi3/SummaryBot/assets/141587110/bd61cae7-2082-4a6f-9259-7cecd6e13fb9)
![sum2](https://github.com/LavanyaPasumarthi3/SummaryBot/assets/141587110/6fbe48ac-bcc4-464c-919b-ac4e220596c3)

## Acknowledgments

This project relies on the OpenAI GPT-3.5 model and is inspired by the capabilities it offers for text summarization.

