
# PDF Text Extraction and Question Generation

This repository contains code for extracting text from PDF documents using `pdfminer` and a Python notebook for generating boolean, multiple-choice questions (MCQ), and one-word answers. The generated questions and answers are saved in three separate text files.

## PDF Text Extraction

The text extraction code is located in the `sec.py` file. It uses the `pdfminer` library to extract text from PDF files. You can use this code to extract text from your PDF documents and save it in a structured format.

### Usage

To extract text from a PDF, you can use the `sec.py` script as follows:

```bash
python sec.py 
```

## Question Generation

The `AI-Assignment.ipynb` notebook contains code for generating questions and answers based on the extracted text. This notebook utilizes natural language processing techniques to create boolean, MCQ, and one-word questions and their corresponding answers.

### Usage

1. Open the `AI-Assignment.ipynb` notebook using Jupyter Notebook or Google Colab.
2. Follow the instructions within the notebook to load your extracted text and generate questions.

## Generated Files

The questions and answers generated using the `AI-Assignment.ipynb` notebook are saved in three separate text files:

- `Boolean_questions.txt`: Contains boolean questions.
- `MCQ.txt`: Contains multiple-choice questions.
- `one_word_answer_questions.txt`: Contains one-word questions.

