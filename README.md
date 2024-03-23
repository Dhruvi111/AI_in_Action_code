# Chatting with PDF  using Large Language Model

## Introduction

This repository contains a  Notebook file (pdf_text_analysis.ipynb) that demonstrates how to extract text from a PDF file, split it into manageable chunks, convert the chunks into numerical vectors using OpenAI GPT-3 embeddings, and perform question-answering tasks on the PDF content.

## Prerequisites 

Before running the notebook, ensure you have the following:

* Access to Google Colab or a local  Notebook environment
* An API key from OpenAI for using GPT-3
* Necessary libraries installed (e.g., PyPDF2, langchain)

## Instructions

### Obtaining API Key

* Get your API key from OpenAI by creating an account.
* Replace os.environ["OPENAI_API_KEY"] with your API key in the notebook. Ensure you keep your API key confidential.

### Running the Notebook

* Open the Notebook (pdf_text_analysis.ipynb) in Google Colab or a local environment.
* Execute each code cell sequentially by pressing Shift + Enter.

### Interacting with the Notebook 

* You can adjust the query in the provided form to ask questions about the PDF content.
* The notebook will generate answers based on the query and the content of the PDF.

## Description of the Notebook

The notebook performs the following tasks:

* Extracts text from a PDF file stored in Google Drive.
* Splits the extracted text into smaller chunks for easier processing.
* Converts the text chunks into numerical vectors using OpenAI GPT-3 embeddings.
* Performs question-answering tasks on the PDF content using a combination of chunks and queries.
