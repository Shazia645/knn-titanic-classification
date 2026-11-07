# Titanic Survival Prediction using KNN (K-Nearest Neighbors)

A beginner-friendly machine learning project that predicts whether a Titanic passenger survived or not using the **K-Nearest Neighbors (KNN)** algorithm.

## Project Overview
KNN is a supervised learning algorithm that classifies a new data point based on the majority class of its *K* closest neighbors in the training data. In this project, KNN is applied to the Titanic dataset to perform binary classification (Survived / Not Survived).

## Project Structure
KNN_ nearest neighbour/
│── KNN.ipynb      # Jupyter notebook with full code
│── titanic.csv    # Dataset
│── README.md      # Project documentation

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook (VS Code)

## Workflow
1. Load the Titanic dataset
2. Data cleaning (handling missing values, dropping unnecessary columns)
3. Encoding categorical features (e.g., Sex, Embarked)
4. Feature scaling using StandardScaler (KNN is distance-based, so scaling is important)
5. Train-test split
6. Train the KNN classifier
7. Find the best value of K
8. Evaluate the model (Accuracy, Confusion Matrix, Classification Report)

## Results
- Best K value: **__** (update with your result)
- Accuracy: **__%** (update with your result)

## Key Learnings
- How the KNN algorithm works (distance-based classification)
- Why feature scaling is necessary for KNN
- How the value of K affects underfitting and overfitting
- Evaluating a classification model

## How to Run
1. Clone the repository
   git clone https://github.com/Shazia645/knn-titanic-classification.git
2. Install the required libraries
   pip install pandas numpy matplotlib seaborn scikit-learn
3. Open `KNN.ipynb` in VS Code or Jupyter Notebook and run all cells.

## Author
**Shazia Batool**
AI Student at COMSATS University | AI Intern at SATA Technologies
GitHub: [Shazia645](https://github.com/Shazia645)