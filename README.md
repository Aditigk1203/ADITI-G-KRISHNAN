# Master EDA Project – Star Dataset Analysis

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) and machine learning techniques applied to a Star Dataset. It is divided into three phases, progressing from basic data exploration and visualization to advanced statistical analysis, clustering, dimensionality reduction, and classification.

The project aims to understand the characteristics of stars, explore relationships between their physical properties, identify patterns and clusters, and classify star types using machine learning.

## 📂 Project Structure

- `Master_EDA.ipynb` – Combined notebook containing Phase 1, Phase 2, and Phase 3 in sequence.
- `README.md` – Project overview, phase descriptions, and instructions.

## 🔬 Project Phases

### Phase 1: Basic Exploratory Data Analysis

The first phase focuses on understanding the dataset and preparing it for further analysis.

**Key activities:**
- Loading the Star Dataset and importing the required Python libraries.
- Examining dataset dimensions, column names, data types, and statistical summaries.
- Identifying and handling missing values.
- Checking for duplicate records and performing data cleaning.
- Applying data transformation techniques.
- Conducting univariate analysis using histograms, count plots, and box plots.
- Performing bivariate analysis to examine relationships between star properties.
- Exploring multivariate relationships using correlation analysis and pair plots.

**Objective:** To understand the dataset's structure, data quality, distributions, and relationships between variables.

### Phase 2: Advanced Statistical Analysis and Clustering

The second phase explores statistical relationships among numerical and categorical star properties and applies unsupervised learning techniques.

**Key activities:**
- Performing one-dimensional statistical analysis using measures such as skewness and kurtosis.
- Conducting two-dimensional statistical analysis to study relationships between variables.
- Calculating Spearman correlation to examine relationships between temperature and luminosity.
- Comparing temperature statistics across star-colour categories using group-wise aggregation.
- Performing multivariate analysis using correlation matrices and pair plots.
- Applying K-Means clustering to group similar observations.
- Performing hierarchical clustering using single-linkage and related cluster analysis steps.

**Objective:** To identify statistical patterns, understand relationships between stellar properties, and explore groups of stars with similar characteristics.

### Phase 3: Dimensionality Reduction and Classification

The third phase introduces dimensionality reduction and supervised machine learning for star-type prediction.

**Key activities:**
- Loading the dataset and cleaning column names.
- Applying Principal Component Analysis (PCA) to reduce numerical features to two principal components.
- Visualizing the reduced feature space to explore patterns in the data.
- Splitting the data into training and testing sets.
- Training a Random Forest Classifier to predict star types.
- Evaluating classification performance using accuracy.
- Visualizing the confusion matrix to examine prediction results.
- Analyzing feature importance to understand which features contribute to classification.

**Objective:** To simplify the feature space, explore the underlying data patterns, and evaluate a machine learning model for star-type classification.

## 🛠️ Technologies and Libraries

- **Python** – Programming language
- **Pandas and NumPy** – Data manipulation and numerical computations
- **Matplotlib and Seaborn** – Data visualization
- **SciPy** – Statistical analysis
- **Scikit-learn** – Clustering, PCA, and machine learning

## 📊 Dataset

**Dataset:** Stars Type Dataset

**Source:** [Stars Type Dataset – GitHub](https://raw.githubusercontent.com/salemprakash/EDA/main/Data/stars%20type.csv)

The dataset contains stellar properties such as temperature, luminosity, and star colour, along with other features used for exploratory analysis and star-type classification.

## ⚙️ How to Run the Project

1. Clone or download this repository.
2. Open `Master_EDA.ipynb` using Jupyter Notebook or Google Colab.
3. Install the required libraries if they are not already available.
4. Run the notebook cells sequentially, beginning with Phase 1, followed by Phase 2 and Phase 3.
5. Review the generated statistical summaries, visualizations, clustering results, PCA plots, and classification evaluation.

**Note:** The notebook retains the existing outputs from all three original phase notebooks. Re-running cells may regenerate outputs and may require the dataset to be accessible.

## 🎯 Conclusion

This project demonstrates a structured approach to analysing a star dataset through three stages. Phase 1 establishes a foundation through data cleaning and exploratory visualization. Phase 2 extends the analysis through statistical methods and clustering. Phase 3 applies PCA and Random Forest classification to investigate feature patterns and predict star types.

Together, these phases provide practical experience in data preprocessing, statistical analysis, visualization, unsupervised learning, dimensionality reduction, and supervised machine learning.

---

**Project:** Master EDA – Star Dataset Analysis  
**Student:** Aditi Krishnan  
**Registration Number:** 23BDS0054
