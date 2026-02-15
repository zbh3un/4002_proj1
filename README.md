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
- data:
-   Link to Kaggle dataset for downloading
-   Data Appendix
- scripts:
-   project1.ipynb - data cleaning and exploratory data analysis
-   official_code.ipynb - VADER sentiment analyzer and Hugging Face transformer based model
- output:
-   figures & tables 

## Section 3: Instructions for Reproducing Results
To reproduce the results, first clone this repository and ensure that the folder structure remains unchanged. This project was developed using Python 3.10 in Google Colab but can also be run in Jupyter Notebook. Before running any notebooks, install the following required packages: pandas, numpy, matplotlib, scipy, vaderSentiment, transformers, torch, and seaborn. Next, download the Spotify reviews dataset using the link provided in the repository and place the CSV file inside the DATA folder. Ensure that the filename matches the filename referenced in the notebooks and do not modify the dataset. Begin by running project1.ipynb from top to bottom. This notebook performs data cleaning, feature engineering, and exploratory analysis. It generates descriptive statistics and visualizations summarizing sentiment distributions and sentiment by star rating. After completing the exploratory analysis, run official_code.ipynb in full. This notebook applies the VADER sentiment analyzer and a Hugging Face transformer-based model to the reviews, computes sentiment scores, evaluates correlation with star ratings, calculates mismatch rates, and compares model performance. All cells must be executed sequentially. Reproduction is successful if both notebooks execute without errors and generate the same summary statistics, correlation results, and visualizations described in the project output.

## References
[1] H. Singh, "Spotify Reviews Dataset," Kaggle, 2022. [Online]. Available: https://www.kaggle.com/code/harshsingh2209/spotify-reviews-sentiment-analysis/input. [Accessed: Feb. 4, 2026].
