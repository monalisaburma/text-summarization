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

## Results

### Facebook-BART

- **ROUGE Scores:**
  - rouge1: Precision - 0.41, Recall - 0.25, F1 Score - 0.31
  - rouge2: Precision - 0.21, Recall - 0.13, F1 Score - 0.16
  - rougeL: Precision - 0.35, Recall - 0.21, F1 Score - 0.26
  - rougeLsum: Precision - 0.38, Recall - 0.23, F1 Score - 0.29

- **Word Overlap Accuracy:** 33.33%

- **Average ROUGE F1 Score:** 0.2536

### T5 (Text-to-Text Transfer Transformer)

- **ROUGE Scores:**
  - rouge1: Precision - 0.44, Recall - 0.24, F1 Score - 0.31
  - rouge2: Precision - 0.21, Recall - 0.11, F1 Score - 0.15
  - rougeL: Precision - 0.35, Recall - 0.19, F1 Score - 0.25
  - rougeLsum: Precision - 0.38, Recall - 0.21, F1 Score - 0.27

- **Word Overlap Accuracy:** 36.36%

- **Average ROUGE F1 Score:** 0.2456

### DistilBERT

- **ROUGE Scores:**
  - rouge1: Precision - 0.44, Recall - 0.24, F1 Score - 0.31
  - rouge2: Precision - 0.21, Recall - 0.11, F1 Score - 0.15
  - rougeL: Precision - 0.35, Recall - 0.19, F1 Score - 0.25
  - rougeLsum: Precision - 0.38, Recall - 0.21, F1 Score - 0.27

- **Word Overlap Accuracy:** 36.36%

- **Average ROUGE F1 Score:** 0.2456


## Conclusion

This text summarization project leverages powerful OpenLLMs, including Facebook-BART, T5, and DistilBERT, to generate concise and informative summaries from news articles. The models demonstrate varying strengths in terms of precision, recall, and word overlap accuracy. While each model contributes uniquely, a careful balance must be struck to optimize for different evaluation metrics. This project opens avenues for enhanced document understanding and can be further extended for applications in automated content curation, information retrieval, and beyond.



## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
The project makes use of powerful language models provided by OpenLLMs, including Facebook-BART, T5, and DistilBERT.

