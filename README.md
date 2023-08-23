# Text Summarization Using spaCy

This project showcases a basic text summarization technique implemented in Python using the spaCy NLP library. The purpose of this project is to generate concise summaries of input text by extracting key sentences based on the frequency of their constituent words.

## Features

- Utilizes spaCy for efficient natural language processing tasks.
- Implements extractive summarization to retain sentences from the original text.
- Calculates word frequencies to determine the importance of each word.
- Scores sentences based on the sum of normalized word frequencies.
- Adjustable summary length to customize the output.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/text-summarization.git`
2. Navigate to the project directory: `cd text-summarization`
3. Install dependencies: `pip install -r requirements.txt`
4. Modify `input_text.txt` with the text to be summarized.
5. Run the script: `python summarize_text.py`

## How It Works

1. Tokenizes the input text, calculating word frequencies while excluding common stopwords and punctuation.
2. Assigns scores to sentences based on the normalized frequencies of their words.
3. Selects the top-scoring sentences for inclusion in the final summary.

## Customization

- Experiment with different spaCy language models for improved tokenization.
- Adjust the length of the summary by modifying the `select_length` variable in the code.

## Contributions

Contributions, bug reports, and feature requests are welcome! Feel free to open issues or submit pull requests.
