# AI Text Summarizer using T5 Transformer

An intelligent abstractive text summarization application built using the T5 Transformer model, FastAPI, and Hugging Face Transformers. This project allows users to input long text and generate concise, meaningful summaries.

It demonstrates practical Natural Language Processing (NLP) and transformer-based text generation in a real-world use case.

---

## Features

* Abstractive text summarization using T5 Transformer
* Fast processing for paragraph-level text
* Simple and clean interface
* Structured project for easy understanding
* Suitable for articles, blogs, and reports

---

## Tech Stack

* Python
* FastAPI
* Hugging Face Transformers
* PyTorch
* HTML / CSS
* Jupyter Notebook

---

## Model Used

This project uses the T5 Transformer model for text summarization.

Model: t5-small
Task: Text Summarization
Framework: Hugging Face Transformers

T5 is a transformer-based model that generates human-like summaries by understanding the context of the input text.

---

## Screenshots

### Home Interface

![Home](Screenshots/Home.png)

### Input Text

![Input](Screenshots/Input.png)

### Generated Summary

![Output](Screenshots/Output.png)

---

## Project Structure

Text Summarizer App/
│── app.py
│── Text_Summarizer_Using_HuggingFace_Transformer.ipynb
│── requirements.txt
│── Templates/
│── Screenshots/
│── .gitignore
│── README.md

---

## Installation & Setup

### Clone the repository

git clone https://github.com/shazia-anwar/Ai-Text-Summarizer.git
cd Ai-Text-Summarizer

### Install dependencies

pip install -r requirements.txt

### Run the application

uvicorn app:app --reload

### Open in browser

http://127.0.0.1:8000

---

## Use Cases

* Summarizing long articles
* Blog and news summarization
* Academic content summarization
* Quick document understanding
* NLP project demonstration

---

## Future Improvements

* PDF file summarization
* DOCX file support
* Download summary feature
* Deployment on cloud platforms
* Improved model for better accuracy

---

## Author

Shazia Anwar (Shaz)
Aspiring AI & Machine Learning Developer
GitHub: https://github.com/shazia-anwar

---

If you find this project helpful, feel free to ⭐ the repository.
