# Cuisine Prediction

## Required Python Packages
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `seaborn` 
- `scipy`
- `umap`
- `pickle`
- `jupyter`

## Files
1. `summary_stats.ipynb` - To collect summary statistics of the cuisines dataset (part of the EDA).
2. `pca_umap.ipynb` - To perform linear PCA and a UMAP visualisation of the cuisines dataset (part of the EDA).
3. `tdidf.ipynb `- To perform TFIDF on the cuisines dataset and formulate the data into a 'bag of ingredients'
4. `baseline_experiments.ipynb` - An initial comparison of common ML models for predicting cuisines.
5. `hyperparameter_tuning.ipynb` - Hyperparameter tuning of the best performing model identified in `baseline_experiments`.

## Running the Code
To run one of the notebooks, clone the repository and find your way to where it is now saved on your local machine. Change your working directory to this repository, and fire up a `jupyter` host by running `jupyter notebook` (ensure all required packages are installed). You can now click on the notebook you are interested in and use Shft+Enter to run the cells. Note, all data can be found in the `datasets` folder and any additional data you wish to add should be stored there.
