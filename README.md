# ML-Project Repository: Model Exploration and Analysis

This repository contains Jupyter notebooks exploring multiple machine learning models applied to different datasets. Each notebook includes preprocessing steps, model training, and evaluation. Below is a description of the repository contents and guidelines for using the notebooks.

## How to Use
1. Start by running the preprocessing blocks in the notebook to prepare the dataset. This is essential as each model depends on a preprocessed dataset for optimal performance.
2. After preprocessing, you can execute the block corresponding to the model you wish to explore.
3. If you'd like to test another model, rerun the preprocessing steps and then execute the block for that model.

## Notebooks in the Repository

### `/Ml-Project1-Nangara.ipynb`
This notebook focuses on predicting the `Default` feature in the test dataset using the following models:
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **XGBoost**

#### Key Details:
- Basic preprocessing is performed at the beginning.
- Additional preprocessing steps for feature enhancement are applied in specific cells for some models.
- Each cell contains complete setups, including train-test splitting and outputting predictions to a CSV file.
- The **XGBoost** model (last cell) was the best performer in this project.
- To use any model:
  1. Run the preprocessing blocks at the start.
  2. Execute the desired model block independently.

### `/Nangara_proj2.ipynb`
This notebook explores the following models:
- **Logistic Regression**
- **Support Vector Machines (SVM)**
- **Neural Networks**

#### Key Details:
- Experiments are conducted with and without skewness handling.
- **Neural Network without SMOTE** emerged as the best-performing model due to its high accuracy and ability to capture complex patterns.
- SMOTE-based balancing enhanced recall but slightly reduced overall accuracy.
- SVM required significant computational resources, making it the most time-intensive model in this analysis.

### Notes
- Select models based on the trade-offs between performance and computational efficiency for your specific use case.
- Ensure to rerun preprocessing steps before trying a different model in the same notebook.

Happy experimenting!
