# Sentiment Analysis with VADER and roBERTa

This project performs **sentiment analysis** on user reviews from a women's clothing e-commerce website using two powerful models: **VADER** (Valence Aware Dictionary and sEntiment Reasoner) and **RoBERTa** (a transformer-based model from Hugging Face). The goal is to determine the sentiment (positive, neutral, or negative) of customer reviews, which can be valuable for understanding customer satisfaction and improving business strategies.

## Project Overview

The project is divided into several steps:
1. **Data Loading and Preparation**: We use a dataset of reviews from an online women's clothing store. The data is preprocessed and cleaned to facilitate further analysis.
2. **Exploratory Data Analysis (EDA)**: Basic insights into the dataset are extracted, including distributions of ratings, review lengths, and other factors.
3. **Sentiment Analysis**:
   - **VADER**: A lexicon-based sentiment analysis tool that is especially good for analyzing social media text.
   - **RoBERTa**: A transformer-based model fine-tuned for sentiment analysis using the Hugging Face Transformers library.
4. **Comparison of Results**: The results of the sentiment analysis using both VADER and RoBERTa are compared to determine which approach provides better insights for this dataset.

## Technologies Used

- **Python**: Main programming language used for analysis.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib** & **Seaborn**: For data visualization.
- **NLTK**: For natural language processing tasks.
  - Tokenizers, part-of-speech taggers, and chunkers.
- **VADER**: For lexicon-based sentiment analysis.
- **Hugging Face Transformers (RoBERTa)**: For deep learning-based sentiment classification.
- **Jupyter Notebook**: For creating and running the analysis in an interactive environment.

## Installation and Setup

### Prerequisites

- Python 3.x
- Jupyter Notebook (optional, but recommended)
  
### Required Libraries

You can install the required libraries using `pip`. Run the following command:

```bash
pip install pandas numpy matplotlib seaborn nltk transformers
