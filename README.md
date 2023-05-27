# Chatbot

## Overview

Chatbot is a Python-based conversational agent that can answer queries about chatbots. It uses the TF-IDF algorithm to calculate the similarity between user input and a corpus of sentences. The chatbot provides responses based on the most similar sentence in the corpus.

## Requirements

- Python 3.x
- `nltk` library

## Installation

1. Clone the repository:

[https://github.com/lorenzilarissa/conversational-ai-chatbot.git](https://github.com/lorenzilarissa/conversational-ai-chatbot/)

2. Install the required dependencies:

`pip install nltk`

3. Download the NLTK packages:

`python -m nltk.downloader popular`

`python -m nltk.downloader punkt`

`python -m nltk.downloader wordnet`

4. Run the notebook:

- Open the `convertional_chatbot.ipynb` notebook.

## Usage

1. Open a terminal or command prompt and navigate to the project directory.

2. Run the Python script:

`python chatbot.py`

3. The chatbot will greet you and prompt you to enter your queries. You can ask questions or have a conversation about chatbots.

4. To exit the chatbot, simply type "bye" and press Enter.

## Customization

You can customize the chatbot by modifying the `GREETING_INPUTS` and `GREETING_RESPONSES` variables in the `chatbot.py` file. These variables define the greetings the chatbot recognizes and the corresponding responses.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
