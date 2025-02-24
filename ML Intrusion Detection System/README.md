# Buidling an Intrusion Detection System
Binary and Multi class classification

## Dataset (Download link):  NF-UNSW-NB15
https://rdm.uq.edu.au/files/c31a9f50-ef99-11ed-ab7b-c7846b13c8a9
or go to : https://staff.itee.uq.edu.au/marius/NIDS_datasets/

## Description

This project focuses on building an Intrusion Detection System (IDS) using machine learning techniques for binary and multi-class classification of network traffic. The goal is to accurately identify malicious activities within a network by analyzing network flow data. 

**Binary Classification:** The model distinguishes between benign and malicious traffic.
**Multi-Class Classification:** The model classifies traffic into specific attack types (e.g., DoS, Exploits, etc.).

The project utilizes the UNSW-NB15 dataset, a comprehensive collection of network flow data with labeled attack categories. Preprocessing steps like data balancing, feature scaling, and log transformation are applied to improve model performance. The project explores various classification models, including Random Forest, SVM, and Neural Networks, to evaluate their effectiveness in detecting intrusions.

## Features

- **Data Preprocessing:** 
    - Handles imbalanced data through oversampling and undersampling.
    - Applies logarithmic transformation to large-range features.
    - Scales features using MinMaxScaler for better model training.
- **Binary Classification:**
    - Distinguishes between benign and malicious network traffic.
    - Employs Random Forest and other models (SVM, Neural Networks) for classification.
- **Multi-Class Classification:**
    - Classifies traffic into specific attack categories (e.g., DoS, Exploits, etc.).
    - Leverages Random Forest and other models for multi-class prediction.
- **Feature Importance Analysis:**
    - Identifies the most significant features contributing to accurate classification.
    - Provides insights into the underlying patterns of network intrusions.
- **Data Visualization:**
    - Includes comprehensive visualizations of data distributions, correlations, and PCA results.
    - Offers insights into dataset characteristics and model performance.

## Getting Started

### Prerequisites

- **Google Colab:** The project is designed to run in a Google Colab environment.
- **Python 3:** The code is written in Python 3 and utilizes libraries like PySpark, scikit-learn, and matplotlib.
- **UNSW-NB15 Dataset:** You'll need to download and upload the UNSW-NB15 dataset to your Google Colab environment.
- **Pyspark, Findspark, py4j:** You need to install these packages using pip install to perform analysis using pyspark dataframe and models.

### Usage Example

1. **Open the Colab Notebook:** Open the provided Google Colab notebook for the project.
2. **Upload Dataset:** Upload the `UNSW-NB15.csv` dataset to your Colab environment.
3. **Install Packages** If you are opening for the first time in google colab, you need to install required packages using `pip install pyspark`, `pip install findspark`, `pip install py4j`.
4. **Run Cells:** Execute the notebook cells sequentially to perform data loading, preprocessing, model training, and evaluation.
5. **Visualizations:** The notebook includes visualizations that will be generated automatically as you run the cells.
6. **Experiment:** Try adjusting model parameters, feature selections, or using different classification models to explore various approaches.
  


## License

This project is licensed under the GNU General Public License v2.0 - see the [LICENSE](./LICENSE) file for details.

## Contact
LinkedIn : [SpecOp7](https://www.linkedin.com/in/specop7)

Certainly! Enhancements and advancements can always be implemented in future versions to further improve functionality. If you have any specific ideas or features you'd like to incorporate in the next version, feel free to share them for consideration.
