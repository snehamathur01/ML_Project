This project applies Machine Learning (ML) techniques to tackle a medical problem: classifying genetic mutations into one of nine categories. The goal is to predict the likelihood of cancer based on gene-variation pairs and corresponding medical text data.

** The dataset includes two files: **

1. Genetic Mutations File: Contains information about the genetic mutations (training_variants).
2. Clinical Evidence File: Contains textual clinical literature used by experts to classify mutations (training_text).

Target Categories
The model predicts one of the following nine categories (class labels from 1 to 9):

Likely loss-of-function
Likely gain-of-function
Neutral
Loss-of-function
Likely neutral
Inconclusive
Gain-of-function
Likely switch-of-function
Switch-of-function
Some of these categories represent malignant mutations, while others are benign or neutral.


** Tools and Libraries **
Python: The primary programming language.
Scikit-learn: For preprocessing, modeling, and evaluation.
Pandas: For data manipulation and analysis.
Matplotlib/Seaborn: For data visualization.
Numpy: For numerical computations.
NLTK: For text preprocessing.
