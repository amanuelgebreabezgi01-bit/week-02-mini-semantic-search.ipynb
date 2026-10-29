# Week 2: Mini Semantic Search

## Overview
This project searches FAQ data by meaning rather than exact keywords.

## Features
- Loads FAQ data using Pandas
- Cleans questions and answers
- Splits text into chunks
- Creates embeddings using Sentence Transformers
- Stores and searches embeddings with ChromaDB
- Prints the top 3 matching FAQ chunks

## Example queries
- I forgot my login details and cannot access my account
- I need a copy of my payment receipt
- I want to stop my monthly plan

## Requirements
Install dependencies with:

pip install -r requirements.txt

## How to run
Open the notebook in Google Colab and run its cells from top to bottom.

## Dataset
The notebook creates a sample FAQ dataset and saves it as faqs.csv.
