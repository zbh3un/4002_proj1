## Section 1: Software and Platform

### Software Used
- Python
- Google Colab

### Required Python Packages
- pandas
- numpy
- matplotlib
- vaderSentiment
- emoji
- scipy

## Section 2: Map of Documentation
DATA Folder

Data_Appendix.pdf – Data appendix describing variables 

reviews.csv file – link to Spotify reviews dataset 

SCRIPTS Folder

project1.ipynb – Performs data cleaning, feature engineering, and exploratory data analysis

official_code.ipynb – Performs sentiment analysis using VADER and a Hugging Face transformer model on the emoji-cleaned dataset, computes correlations and mismatch rates in the dataset without emojis

official_code_w_emojis - Performs sentiment analysis using VADER and a Hugging Face transformer model on the original dataset including emojis, computes correlations and mismatch rates in the dataset with the emojis 

OUTPUT Folder

Output.pdf - Document containing all visualizations and table outputs


## Section 3: Instructions for Reproducing Results
To reproduce the results, first clone this repository and ensure that the folder structure remains unchanged. This project was developed using Python 3.10 in Google Colab but can also be run in Jupyter Notebook. Before running any notebooks, install the following required packages: pandas, numpy, matplotlib, scipy, vaderSentiment, transformers, torch, and seaborn. Next, download the Spotify reviews dataset using the link provided in the repository and place the CSV file inside the DATA folder. Ensure that the filename matches the filename referenced in the notebooks and do not modify the dataset. Begin by running project1.ipynb from top to bottom. This notebook performs data cleaning, feature engineering, and exploratory analysis. It generates descriptive statistics and visualizations summarizing sentiment distributions and sentiment by star rating. After completing the exploratory analysis, run official_code.ipynb in full. After completing the exploratory analysis, run official_code_w_emojis.ipynb in full, which applies emoji preprocessing and implements both the VADER sentiment analyzer and the Hugging Face transformer-based model. Finally, run official_code.ipynb, which performs the core model comparison, computes evaluation metrics including exact match accuracy, off-by-one accuracy, and average error, as well as generates confusion matrices and error distributions, and displays comparative results. Reproduction is successful if all notebooks execute without errors and generate the same summary statistics, performance metrics, and visualizations described in the project output.

## References
[1] H. Singh, "Spotify Reviews Dataset," Kaggle, 2022. [Online]. Available: https://www.kaggle.com/code/harshsingh2209/spotify-reviews-sentiment-analysis/input. [Accessed: Feb. 4, 2026].
