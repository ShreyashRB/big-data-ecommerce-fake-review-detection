Detecting Mismatched and Fake Listings on E-Commerce via a Multimodal AI Pipeline

This repository contains the code for Assignment 1 (Part B and Part C) of the Big Data Analysis and Project (COMP_SCI_7209) course. The project aims to detect mismatched and fake listings on e-commerce platforms using a multimodal AI pipeline.


The goal of this project is to identify suspicious product listings on online shopping websites, specifically focusing on the 'All Beauty' category from an Amazon product dataset. 
The system combines data from product reviews, metadata, and price to construct a robust 'authenticity score' for each product listing.

finalCodeForPartC.ipynb: Jupyter Notebook containing the final code for Part C, including data preprocessing, feature engineering, model selection, hyperparameter tuning, and 
evaluation of machine learning models for suspicious review detection.

bigdatapartBcode.ipynb: Jupyter Notebook containing the code for Part B, which focuses on initial data exploration, visualization, and raw data analysis.


How to Run the Code

To run the Jupyter Notebooks, you will need to have Python and Jupyter installed. 

1.Clone the repository:

2.Install dependencies:
It is recommended to install the required libraries using pip.

3.
Prepare the data:
The notebooks expect the first10kreviewsall_beauty.jsonl and first10kmetaall_beauty.jsonl datasets to be available at https://amazon-reviews-2023.github.io/  Please adjust the REVIEWS_PATH and META_PATH variables in the notebooks if your data is located elsewhere.

4.
Run Jupyter Notebook:

