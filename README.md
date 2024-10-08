# Fraud Detection Using Synthesized Data: A Cautionary Tale
**This project performs exploratory data analysis and trains a machine learning model to detect fraud.**
* Highlighted my approach to exploratory data analysis using statistical analysis, data visualization, and feature engineering to search for patterns and insights
* Documented data quality issues and reasoning for the belief that the dataset was overly synthesized
* Trained a logistic regression classifier to explore the limitations of building a viable machine learning model with non-representative data
* Explained why this project is a cautionary tale demonstrating the necessity of representative data that conveys the complexity and noisiness of real-world data

Note:   An HTML rendering of the project notebook can be viewed at: https://nbviewer.org/github/databymir/fraud_fraudsynth/blob/main/fraudsynth.ipynb 
        and a LinkedIn article can be viewed at https://www.linkedin.com/pulse/fraud-detection-using-synthesized-data-cautionary-oliverius-cpa-1ehcc/

## Table of Contents
* [Authors](#authors)
* [Installation](#installation)
* [Data](#data)
* [Code](#code)
* [License](#license)

## Authors 
[@databymir] (https://github.com/databymir)

## Installation
### Codes and Resources Used
* Python Version: 3.12.3
* Jupyter Notebook Version: 7.0.6

### Python Packages Used
#### Data Manipulation
* NumPy Version: 1.26.2
* Pandas Version: 2.1.4

#### Data Visualization
* Matplotlib Version: 3.8.2
* Seaborn Version: 0.13.2

#### Machine Learning
* Scikit-Learn Version: 1.5.2

## Data
### Source Data
The data is a synthetic dataset intended for "the development and evaluation of credit fraud detection models" (Ismail, 2024).

### Data Acquisition
The dataset was acquired by downloading the .csv file from https://www.kaggle.com/datasets/youssefismail20/fraudsynth-credit-fraud-detection-dataset/data. The file is not included in this repository due to file size limitations but can be downloaded directly from Kaggle using that link.

## Code
├── fraudsynth.ipynb

├── LICENSE

├── README.md

└── .gitignore

## References
Géron, Aurélien. (2023). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, Third Edition*. O'Reilly Media.

Ismail, Youssef. (2024, February 29). *FraudSynth: Credit Fraud Detection Dataset*. Kaggle. https://www.kaggle.com/datasets/youssefismail20/fraudsynth-credit-fraud-detection-dataset

## License
For this github repository, the License used is [MIT License](https://opensource.org/license/mit/)