# Repository Overview

This repository contains data processing, data transformation, validation and predictive modeling for my thesis. It is focused on behavioural and sentiment analysis for my datatset based on Amazon Beauty. This project contains heavy computional level of semantic embeddings that is applied on customer reviews.

# Models used for analysis
For my project, I have used two predicitve models: *Logistic Regression* and *Random Forest* and these are used to analysis that whether a customer will be churned or retained based on the loyalty signals embedded in the textual reviews. 

# Key Findings
The key findings includes that Word count and the review lenght are more important predictors than ratings is a significantly more sensitive predictor of customer retention than numerical star ratings. Retained customers show a **50.3%** increase in textual volume compared to churned customers, suggesting that loyalty is strongly correlated with narrative-driven feedback.

# Notebook Setup Details
The prerequisites to run the project is to install Python 3.8. Furthermore, the dataset used for analysis had more than **700,000** records. To find embeddings of tokens deducted from data records, it needed GPU And TPU to run BGE-M3 embeddings efficiently.

# Libraries 
To run the analysis you need to download these libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sentence-transformers` (for BGE-M3 embeddings), `scikit-learn`, and `ipywidgets`.

# Steps to run the project
To reproduce the results of this file you need to:
1. Place the `amazon_beauty_reviews_dataset.csv` in the `data/` directory.

2. Open the `notebooks/Final_Thesis.ipynb` in Jupyter Lab or Google Colab.

3. Execute the cells in sequence to perform the data cleaning, embedding generation, and visualization.

4. Refer to Figure 9.2 in the notebook to view the dual-axis visualization illustrating the behavioral divergence between churned and retained customers.