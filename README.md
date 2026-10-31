
# AI Text Summarizer

## Project Overview

The AI Text Summarizer is a Python-based application that uses Natural Language Processing (NLP) to convert lengthy text into shorter, meaningful summaries. It uses a pre-trained DistilBART model from Hugging Face Transformers to identify important information and generate concise summaries while retaining the main ideas of the original content.

The project provides a simple interactive interface where users can enter text, choose their preferred summary length, and view the generated results along with summary statistics.

## Key Features

- Automatically generates summaries from lengthy text.
- Provides different summary length options: Short, Medium, and Long.
- Displays the original and summarized word counts.
- Calculates the percentage of text reduction.
- Offers an interactive interface for easy usage.
- Includes options to generate summaries and clear the input and output.

## Technologies Used

- **Programming Language:** Python
- **Concept:** Natural Language Processing (NLP)
- **Deep Learning Framework:** PyTorch
- **Pre-trained Model:** DistilBART
- **NLP Library:** Hugging Face Transformers
- **Development Environment:** Jupyter Notebook
- **Interface:** ipywidgets

## Pre-trained Model

This project uses the following pre-trained model:

**Model:** `sshleifer/distilbart-cnn-12-6`

**Hugging Face:** https://huggingface.co/sshleifer/distilbart-cnn-12-6

DistilBART is a Transformer-based model designed for text summarization. It helps generate shorter versions of lengthy content while retaining the key information.

## How the Application Works

1. The user enters a paragraph, article, or other lengthy text.
2. The user selects the preferred summary length.
3. The input text is processed using the Hugging Face tokenizer.
4. The pre-trained DistilBART model generates a summary.
5. The generated summary is displayed in the output section.
6. The application calculates and displays summary statistics.

## Summary Statistics

The application provides three basic measurements:

- **Original Word Count:** Total number of words in the input text.
- **Summary Word Count:** Total number of words in the generated summary.
- **Text Reduction:** Percentage reduction in the text after summarization.

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AI-Text-Summarizer.git
```

### 2. Navigate to the Project Directory

```bash
cd AI-Text-Summarizer
```

### 3. Install the Required Libraries

```bash
pip install transformers torch sentencepiece ipywidgets
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Application

Open `AI_Text_Summarizer.ipynb` and execute the notebook cells in sequence.

## Project Structure

```text
AI-Text-Summarizer/
│
├── AI_Text_Summarizer.ipynb
│
└── README.md
```

## Applications

This application can be useful for:

- Summarizing news articles and blog posts.
- Understanding lengthy educational materials.
- Extracting important information from documents.
- Summarizing research-related content.
- Making large amounts of text easier to read and understand.

## Learning Outcomes

Through this project, I gained practical experience in:

- Understanding Natural Language Processing concepts.
- Working with pre-trained Transformer models.
- Using Hugging Face Transformers for text generation.
- Implementing text summarization using PyTorch.
- Understanding tokenization and model inference.
- Building interactive applications using Python.

## Future Enhancements

Some possible improvements for this project include:

- Adding PDF and DOCX file upload support.
- Supporting multiple languages.
- Developing a standalone web application.
- Improving summarization quality and flexibility.
- Providing an option to download generated summaries.

## Author

**Amjed**

AI & ML Enthusiast

---

This project was developed as part of my learning journey in Artificial Intelligence and Machine Learning.
