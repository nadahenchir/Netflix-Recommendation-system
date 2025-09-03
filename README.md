# netflix-recommendation-system
##Description 
This project implements a Collaborative Filtering Recommender System using the MovieLense dataset in R.
It compares Item-Based CF (IBCF) and User-Based CF (UBCF), evaluates them, and generates Top-N recommendations.
##Installation
You need to install R(>=4.0) and install the required packages (run in R)
The required packages are: recommenderlab, Matrix, dplyr, tidyr and ggplot2.
##Usage 
1) Set working directory to the project root 
in r: setwd("path/to/yourfoldername")
2) Run the script in order 
3) The trained model is saved in models/final_ibcf.rds
   You can load it anytime without retraining: final_model <- readRDS("models/final_ibcf.rds")
##Features
Data exploration (heatmap, histogram)
Model training with IBCF and UBCF
Evaluation with Precision, Recall, NDCG
Final recommender trained on full dataset
Generate Top-10 recommendations for users
##Notes
Notes
The project uses the built-in MovieLense dataset, so no extra data download is needed.
For reproducibility, random seed is set to 42.

