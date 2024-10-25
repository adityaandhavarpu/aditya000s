# Decision Tree and Principal Component Analysis

This repository contains implementations of **Decision Tree** and **Principal Component Analysis (PCA)** models for disease prediction and dimensionality reduction tasks.

## Project Structure

- **Part 1: Decision Tree for Disease Prediction**
  - **Objective**: Predict diabetes presence based on medical features.
  - **Datasets**:
    - `diabetes.csv`: Noiseless dataset
    - `diabetes_noise.csv`: Noisy dataset
  - **Method**: Decision Tree Classifier
  - **Evaluation**: Compare performance between noiseless and noisy data.

- **Part 2: PCA for Dimensionality Reduction**
  - **Objective**: Perform dimensionality reduction on the wine quality dataset.
  - **Dataset**: `wine-quality.csv` with `Customer_Segment` as the target variable.
  - **Method**: Principal Component Analysis (PCA)

## Files

- `22EE30003_A2_Part1.ipynb`: Jupyter notebook for the Decision Tree model
- `22EE30003_A2_Part2.ipynb`: Jupyter notebook for the PCA model
- `22EE30003_report.pdf`: Report summarizing results and observations

## Requirements

- Python 3.7+
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

## Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. Run each Jupyter notebook:
    - Open `22EE30003_A2_Part1.ipynb` for the Decision Tree implementation.
    - Open `22EE30003_A2_Part2.ipynb` for the PCA implementation.
    - Execute cells sequentially to train models and view results.

3. Review `22EE30003_report.pdf` for a summary and insights from the project.

---

