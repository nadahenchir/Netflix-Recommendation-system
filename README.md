# netflix-recommendation-system
##Description 
This project demonstrates a Collaborative Filtering Recommender System using the MovieLense dataset in R. The recommender predicts top-N movies for users using Item-Based and User-Based Collaborative Filtering.
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



