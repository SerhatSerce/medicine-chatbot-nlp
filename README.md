# Medicine Chatbot NLP Project

---

## Project Overview

This project is an NLP-based medication question answering chatbot system developed using the MedicationQA dataset.

The main goal of the project is to develop a chatbot that can generate meaningful answers to medication-related questions asked by users.

Two different transformer-based text generation models were trained and compared during the project:

- T5-small
- FLAN-T5-small

The system can answer medication-related questions using natural language generation techniques.

---

## Dataset

The project uses the MedicationQA dataset published on Hugging Face.

Dataset Source:  
https://huggingface.co/datasets/truehealth/medicationqa

The dataset contains:

- Medication names
- User questions
- Reference answers

The dataset was preprocessed and divided into:

- Training set
- Validation set
- Test set

---

## Technologies Used

- Python
- Hugging Face Transformers
- PyTorch
- Pandas
- Datasets
- Gradio
- Scikit-learn
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## Project Structure

```text
medicine-chatbot-nlp/
│
├── data/
├── notebooks/
├── reports/
├── screenshots/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Models

### 1. T5-small

T5-small is a lightweight transformer model designed for text-to-text NLP tasks.

Used for:

- Question answering
- Text generation
- Natural language response generation

---

### 2. FLAN-T5-small

FLAN-T5-small is an instruction-tuned version of T5.

Advantages:

- Better understanding of user prompts
- More natural responses
- Improved contextual understanding

---

## Training Process

The models were fine-tuned using the MedicationQA dataset.

Training pipeline includes:

1. Dataset preprocessing
2. Train/validation/test split
3. Tokenization
4. Model training
5. Evaluation
6. Chatbot interface development

---

## Evaluation

The models were evaluated using:

- BLEU Score
- ROUGE Score

Model outputs were compared with reference answers from the dataset.

---

## Chatbot Interface

A Gradio-based web interface was developed for testing the chatbot.

Features:

- User question input
- Real-time response generation
- Simple and user-friendly interface

---

## Example Questions

- What is this medicine used for?
- Can I take this drug with food?
- What should I do if I miss a dose?

---

## Installation

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Run the notebooks in order:

1. Dataset Preparation
2. T5 Model Training
3. Gradio Chatbot
4. FLAN-T5 Training
5. Model Evaluation

---

## Important Note

This project was developed for academic and educational purposes only.

The chatbot should not be used as a real medical advisory system.

---

## Authors

- Serhat Serce
- Emir Yusuf Çiçekdemir