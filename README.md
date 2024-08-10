# NIPS Papers Analysis

This project analyzes research papers published at the Neural Information Processing Systems (NIPS) conference from 1987 to 2017, stored in `datasets/papers.csv`.

## Steps in the Analysis:

1. **Data Loading:**  
   Load and explore the dataset containing paper titles, abstracts, and full texts.

2. **Data Preparation:**  
   Remove unnecessary columns, retaining only text data for natural language processing (NLP) analysis.

3. **Trend Visualization:**  
   Plot the number of papers published each year to visualize the growth in machine learning research.

4. **Text Preprocessing:**  
   Clean titles by removing punctuation and converting them to lowercase.

5. **Word Cloud Generation:**  
   Generate a word cloud to visualize the most common words in paper titles.

6. **LDA Topic Modeling:**  
   Use Latent Dirichlet Allocation (LDA) to identify key topics in the research papers.

## Getting Started:

1. **Install Dependencies:**  
   Ensure you have Python and libraries like `pandas`, `matplotlib`, `scikit-learn`, and `wordcloud`.

2. **Run the Analysis:**  
   Execute the Jupyter notebook to load, preprocess, and analyze the data.
