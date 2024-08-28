# Fake Review Detection Project

This repository contains the code, datasets, and report for my MSc project titled **"Enhancing Fake Review Detection with Cross-Platform Analysis Using Supervised and Deep Learning Models and Feature Engineering Evaluation."**

## Project Overview

The primary objective of this project was to develop and evaluate machine learning and deep learning models for detecting fake reviews across multiple e-commerce platforms. The project addressed several key challenges, including:

- Cross-platform adaptability
- The impact of feature engineering
- Comparison between supervised and deep learning approaches
- The integration of user feedback

## Repository Structure

### Data Folder
- **datasets.rar**: A compressed file containing the initial datasets (Amazon_1.csv, Amazon_2.csv, Amazon_3.txt, Hotels.csv, Yelp_1.csv) sourced from various platforms like Amazon, Yelp, and Hotels. These datasets were merged to create a cross-platform dataset.
- **final_dataset.csv**: The dataset created by merging and sampling the initial datasets.
- **modified_dataset.csv**: The final dataset after feature engineering, used for model training and evaluation.
- **modified_feedback.csv**: A dataset simulating user feedback for retraining models.
- **modified_test.csv**: A test dataset containing new, unseen data used to evaluate the models' generalization capabilities.

### Code Folder
- **Data Cleaning & Dataset Creation.ipynb**: Contains the code for cleaning the initial datasets and creating the final dataset.
- **Deep Learning Model Development.ipynb**: Implementation and evaluation of deep learning models like LSTM, CNN-LSTM, and LSTM-RNN.
- **Exploratory Data Analysis.ipynb**: Code for performing exploratory data analysis on the dataset, including visualizations like box plots and word clouds.
- **Feature Engineering for Simulated User Feedback Data.ipynb**: Code for feature engineering applied to the dataset used for simulating user feedback.
- **Feature Extraction & Engineering.ipynb**: Code for feature extraction and engineering applied to the main dataset.
- **Supervised Model Training & Performance Evaluation.ipynb**: Training and evaluation of supervised models (KNN, SVM, RF, LR).
- **Supervised Model Training Without Feature Engineering.ipynb**: Comparison of supervised model performance without feature engineering.

### Report
- **Report.docx**: The final project report, detailing the research methodology, results, and conclusions.

### Project overview presentation
- **Project_overview.pptx**: This presentation includes key visualizations and summaries of the methodology, findings, and conclusions. 

## How to Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/f2-bigdeli/Fake-Review-Detection.git
    ```
2. **Data Preparation:**
    - Extract the datasets.rar file to access the initial datasets. The data folder contains all necessary datasets, and the notebooks are set up to read from this folder directly.

3. **Run Notebooks:**
    - Open the Jupyter notebooks in the `code` folder to explore the data, perform feature engineering, and train models.

4. **View Report:**
    - The final report is available as `Report.docx` for a detailed understanding of the research process and findings.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



