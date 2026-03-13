# Simple Semantic Search Engine with Embeddings

## Project Overview

This project builds a **semantic search engine** that retrieves documents based on **meaning** rather than exact keywords.

The system converts text into **vector embeddings** and computes **similarity scores** between query and documents to find the most relevant results.

## Dataset

* No large dataset is used.
* Example sentences or short text documents are included in `data/sample_texts.txt`.
* You can extend it with your own text corpus.

## Objectives

* Learn how to convert text into embeddings
* Compute semantic similarity between query and documents
* Build a simple search interface for semantic retrieval

## Methods and Tools

* Sentence embeddings (e.g., via **SentenceTransformers**, **spaCy**, or **OpenAI embeddings**)
* Cosine similarity for ranking
* Python libraries: Pandas, NumPy, scikit-learn

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-Learn
* Jupyter Notebook
* Optional: SentenceTransformers or Hugging Face

## Project Workflow

1. Load sample text documents
2. Convert text to embeddings
3. Accept query input
4. Compute similarity scores
5. Retrieve and rank top results
6. Display results

## Example Output

Query: `"machine learning in healthcare"`
Top 3 matched documents:

1. "Applications of machine learning in healthcare diagnosis."
2. "Healthcare data and predictive modeling using ML."
3. "Deep learning methods for medical image analysis."

#
