🌸 Principal Component Analysis (PCA) on Iris Dataset

A machine learning project that applies Principal Component Analysis (PCA) to the famous Iris flower dataset to reduce dimensionality and visualize data patterns effectively.

📌 Project Overview

This project demonstrates how PCA can transform high-dimensional data into a lower-dimensional space while preserving maximum variance.

The dataset used is the classic Iris dataset, widely used for machine learning and statistical analysis.

🎯 Objectives

Load and explore the Iris dataset

Standardize features

Apply Principal Component Analysis

Reduce 4-dimensional data into 2 principal components

Visualize species separation

Analyze explained variance

📊 Dataset Information

The Iris dataset contains:

150 samples

3 species:

Setosa

Versicolor

Virginica

4 features:

Sepal Length

Sepal Width

Petal Length

Petal Width

🧠 What is PCA?

Principal Component Analysis (PCA) is a dimensionality reduction technique that:

Converts correlated variables into uncorrelated principal components

Orders components by variance explained

Helps visualize complex datasets

Reduces noise and redundancy

🛠️ Technologies Used

Python 3.x

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

📂 Project Structure
PCA-Iris-Analysis/
│
├── Principal_Component_Analysis_iris.ipynb   # Main notebook
├── README.md                                 # Project documentation
🚀 How to Run the Project
1️⃣ Clone Repository
git clone https://github.com/your-username/PCA-Iris-Analysis.git
cd PCA-Iris-Analysis
2️⃣ Install Dependencies
pip install numpy pandas matplotlib seaborn scikit-learn
3️⃣ Launch Jupyter Notebook
jupyter notebook

Open:

Principal_Component_Analysis_iris.ipynb
📈 Key Steps in Notebook
🔹 Data Loading

Import dataset using sklearn.datasets

Convert to Pandas DataFrame

🔹 Data Preprocessing

Feature scaling using StandardScaler

🔹 Applying PCA

Use sklearn.decomposition.PCA

Reduce to 2 principal components

🔹 Visualization

Scatter plot of Principal Component 1 vs Principal Component 2

Color-coded by species

Explained variance ratio plot

📊 Results

Reduced 4D feature space to 2D

Clear separation of Setosa species

Partial overlap between Versicolor and Virginica

First two components explain majority of variance

💡 Key Learnings

Importance of feature scaling before PCA

Interpretation of eigenvalues and eigenvectors

Dimensionality reduction without significant information loss

Visualization of high-dimensional data

🔮 Future Enhancements

Apply K-Means clustering after PCA

Compare PCA with LDA

Deploy as a Streamlit visualization app

Apply PCA to larger real-world datasets

👨‍💻 Author

Pankaj Mahure
Aspiring Data Scientist | Machine Learning Enthusiast

📜 License

This project is open-source and available for educational purposes.
