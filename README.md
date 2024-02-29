# Text Summarization using OpenLLMs

## Overview

This project focuses on utilizing OpenLLMs (Open Language Models) - Facebook-BART, T5, and DistilBERT, for text summarization. The goal is to create concise and coherent summaries of news articles from the CNN-Dailymail dataset.

## Key Features

- **Data Cleaning and Preprocessing:** Employed natural language processing techniques to clean and preprocess the dataset, ensuring optimal model training.
  
- **Model Evaluation:** Utilized ROUGE scores, word overlap accuracy, and average F1 score for comprehensive model evaluation.

- **State-of-the-Art Models:**
  - **Facebook-BART:** Leveraged the BART model for conditional generation, achieving effective summarization.
  - **T5 (Text-to-Text Transfer Transformer):** Implemented text summarization using the T5 model.
  - **DistilBERT:** Employed DistilBERT for sequence classification to generate informative summaries.

## Usage

- The project includes Jupyter Notebooks (`text_summarization.ipynb`) that guide through the entire process from data loading to model evaluation.

- Users can adapt and extend the project for their own datasets or customize it for specific use cases.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/monalisaburma/text-summarization.git
   ```

### Open and run the Jupyter Notebook text_summarization.ipynb for a step-by-step walkthrough.


## Dependencies
This project uses Python and various libraries. Make sure to install them using:

```bash
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
The project makes use of powerful language models provided by OpenLLMs, including Facebook-BART, T5, and DistilBERT.

