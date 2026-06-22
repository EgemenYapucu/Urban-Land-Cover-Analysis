# Urban Land Cover Analysis

This project focuses on the classification of urban land cover types using machine learning techniques.  
The dataset used in this project is the **Urban Land Cover Dataset** from the UCI Machine Learning Repository.

The main goal of the project is to classify different urban land cover categories by using spectral, shape, size, and texture-based features extracted from high-resolution aerial imagery.

---

## Dataset

The dataset contains training and testing data for classifying urban land cover from high-resolution aerial images.

Dataset source:  
UCI Machine Learning Repository - Urban Land Cover Dataset

The target variable is `class`, which represents the land cover category.

### Land Cover Classes

The dataset includes 9 different urban land cover classes:

- Trees
- Grass
- Soil
- Concrete
- Asphalt
- Buildings
- Cars
- Pools
- Shadows

### Dataset Features

The dataset contains multiple feature groups such as:

- Spectral features
- Shape features
- Size features
- Texture features
- NDVI-related features
- Multi-scale image-based variables

---

## Project Structure

```text
Urban-Land-Cover-Analysis/
├── Data.txt
├── Urban Land Cover Analysis.py
├── training.csv
└── testing.csv
```
### Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib

### Machine Learning Methods

This project applies and compares machine learning models for urban land cover classification.

The main models used are:

Multi-Layer Perceptron Classifier
Gaussian Naive Bayes

The project also includes:

Train-test split
Cross-validation
Z-score normalization
Label encoding
Accuracy, precision, recall, and F1-score evaluation

### Workflow

The general workflow of the project is:

Load training and testing datasets
Combine datasets for preprocessing
Separate features and target variable
Train machine learning models without normalization
Evaluate models using 5-fold and 10-fold cross-validation
Apply z-score normalization
Re-train and re-evaluate the models
Compare classification performance

### Evaluation Metrics

The models are evaluated using the following metrics:

Accuracy
Precision Macro
Recall Macro
F1 Macro

These metrics are used to compare model performance across different cross-validation settings.

### How to Run

Clone the repository:
```
git clone https://github.com/EgemenYapucu/Urban-Land-Cover-Analysis.git
```
Go to the project folder:
```
cd Urban-Land-Cover-Analysis
```
Install the required libraries:
```
pip install pandas numpy scikit-learn matplotlib
```
Run the Python script:
```
python "Urban Land Cover Analysis.py"
```
### Dataset Reference

The dataset used in this project is publicly available from the UCI Machine Learning Repository:

Urban Land Cover Dataset
Brian Johnson, 2013
UCI Machine Learning Repository

### Purpose of This Project

This project was created as a machine learning exercise to practice:

Working with real-world classification datasets
Preprocessing tabular data
Applying supervised machine learning algorithms
Comparing model performance with cross-validation
Understanding the use of machine learning in environmental and urban planning problems

### Author

Egemen Yapucu
GitHub: EgemenYapucu


