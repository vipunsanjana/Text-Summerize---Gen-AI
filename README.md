# Text Summarizer and YouTube link summarizer using Hugging Face Transformers

This project is a text summarizer application built using Python and the Hugging Face Transformers library. The summarizer utilizes the `sshleifer/distilbart-cnn-12-6` model, which is a smaller, distilled version of the BART model fine-tuned on the CNN/DailyMail dataset for text summarization tasks.

## Features

- Summarize long articles or text documents into concise summaries.
- Summarize the content of YouTube videos by extracting and summarizing their transcriptions.
- Built using the `transformers` library from Hugging Face.
- Easy-to-use command-line interface.

## Requirements

- Python 3.6+
- `transformers` library
- `torch` (PyTorch library)
- `gradio`
- `youtube-transcript-api`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vipunsanjana/Text-Summerize---Gen-AI
    cd Text-Summerize---Gen-AI
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Text Summarization

You can summarize any text file using the following command:
```bash
python summarize.py --text_file path/to/your/textfile.txt
