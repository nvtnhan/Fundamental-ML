# Mini-Project for Fundamentals of Machine Learning Course
![background](./materials/ai_wp.jpg)
This repository contains the code and data for a mini-project on facial expression recognition using machine learning algorithms.

## 📑 Project Policy
- Team: group should consist of 3-4 students.

    |No.| Student Name    | Student ID |
    | --------| -------- | ------- |
    |1|Nguyễn Vũ Tường Nhân|21110351|
    |2|Trịnh Hoàng Phú|21110370|
    |3|Lê Thanh Tiến|21110409|
    |4|Lê Đăng Nhật|21110354|

- The submission deadline is strict: **11:59 PM** on **June 22nd, 2024**. Commits pushed after this deadline will not be considered.

## 📝 Result
| Algorithms | Data | Macro Avg. Precision | Weighted Avg. Precision | Macro Avg. Recall | Weighted Avg. Recall | Macro Avg. F1-score | Weighted Avg. F1-score | Accuracy |
|---|---|---|---|---|---|---|---|---|
| Logistic Regression | Original | 0.32 | 0.35 | 0.31 | 0.38 | 0.30 | 0.36 | 0.38 |
| Logistic Regression | PCA transformed | 0.31 | 0.34 | 0.29 | 0.38 | 0.28 | 0.34 | 0.38 |
| Naive Bayes | Original | 0.22 | 0.27 | 0.22 | 0.21 | 0.17 | 0.19 | 0.21 |
| Naive Bayes | PCA transformed | 0.31 | 0.33 | 0.27 | 0.34 | 0.25 | 0.29 | 0.34 |
| Random Forest | Original | 0.56 | 0.49 | 0.42 | 0.48 | 0.44 | 0.46 | 0.48 |
| Random Forest | PCA transformed | 0.56 | 0.49 | 0.42 | 0.48 | 0.44 | 0.46 | 0.48 |
| MLP | Original | 0.38 | 0.41 | 0.38 | 0.41 | 0.38 | 0.41 | 0.41 |
| MLP | PCA transformed | 0.41 | 0.39 | 0.41 | 0.39 | 0.41 | 0.39 | 0.41 |


## 📦 Project Structure

The repository is organized into the following directories:

- **/data**: This directory contains the facial expression dataset. You'll need to download the dataset and place it here before running the notebooks. (Download link provided below)
- **/notebooks**: This directory contains the Jupyter notebook ```EDA.ipynb```. This notebook guides you through exploratory data analysis (EDA) and classification tasks.

## ⚙️ Usage

This project is designed to be completed in the following steps:

1. **Fork the Project**: Click on the ```Fork``` button on the top right corner of this repository, this will create a copy of the repository in your own GitHub account. Complete the table at the top by entering your team member names.

2. **Download the Dataset**: Download the facial expression dataset from the following [link](https://mega.nz/file/foM2wDaa#GPGyspdUB2WV-fATL-ZvYj3i4FqgbVKyct413gxg3rE) and place it in the **/data** directory:

3. **Complete the Tasks**: Open the ```notebooks/EDA.ipynb``` notebook in your Jupyter Notebook environment. The notebook is designed to guide you through various tasks, including:
    
    1. Prerequisite
    2. Principle Component Analysis
    3. Image Classification
    4. Evaluating Classification Performance 

    Make sure to run all the code cells in the ```EDA.ipynb``` notebook and ensure they produce output before committing and pushing your changes.

5. **Commit and Push Your Changes**: Once you've completed the tasks outlined in the notebook, commit your changes to your local repository and push them to your forked repository on GitHub.


Feel free to modify and extend the notebook to explore further aspects of the data and experiment with different algorithms. Good luck.
