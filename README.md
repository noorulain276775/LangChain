# LangChain

# Book Recommender

This project helps you explore a dataset of books and recommends books using vector search and semantic analysis. It is designed for beginners interested in data science, machine learning, and recommendation systems.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Usage Guide](#usage-guide)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [How It Works](#how-it-works)

---

## Project Overview
The Book Recommender project analyzes a dataset of books, cleans the data, and uses vector search to recommend books based on semantic similarity. It is implemented in Python using Jupyter notebooks for easy exploration and visualization.

## Features
- Data cleaning and exploration of book features
- Handling missing values and feature engineering
- Saving a cleaned dataset for further analysis
- Semantic search for book recommendations using vector embeddings

## Setup Instructions
1. **Clone the repository**  
   Download or clone this project to your local machine.

2. **Install dependencies**  
   Open a terminal in the project folder and run:
   ```powershell
   pip install -r requirements.txt
   ```
   This will install all required Python packages.

3. **Open Jupyter Notebooks**  
   Launch Jupyter Notebook or JupyterLab and open `dataExploration.ipynb` and `vector-search.ipynb`.

## Usage Guide
- Start with `dataExploration.ipynb` to understand and clean the book dataset.
- Use `vector-search.ipynb` to run semantic search and get book recommendations.

## Project Structure
- `books_cleaned.csv`: Cleaned book dataset for analysis and recommendations.
- `dataExploration.ipynb`: Notebook for exploring and cleaning the data.
- `vector-search.ipynb`: Notebook for semantic search and recommendations.
- `requirements.txt`: List of required Python packages.
- `README.md`: Project documentation (this file).

## Dependencies
All dependencies are listed in `requirements.txt`. Common packages may include:
- pandas
- numpy
- scikit-learn
- sentence-transformers (for vector embeddings)
- matplotlib (for visualization)
- langchain
- chromadb
- python-dotenv

## How It Works
1. **Data Exploration**  
   - Load the raw book dataset.
   - Analyze missing values and correlations.
   - Engineer new features and clean the data.
   - Save the cleaned data to `books_cleaned.csv`.

2. **Semantic Search**  
   - Use vector embeddings to represent book descriptions.
   - Search for books similar to a given query (e.g., "A book to teach children about nature").
   - Retrieve and display recommended books using the ISBN for accurate lookups.
