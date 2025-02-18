# Analyzing Unstructured Data

## Project Overview

This repository contains the project files for the MGTA415 course's final project titled "Traditional Machine Learning Models Outperform Deep Learning on Limited Training Corpous, Taking Restaurant Review as Example." This research explored the comparative performance of traditional machine learning models and deep learning models in a multi-class classification task using a dataset of restaurant reviews.

## Repository Structure

```
/repo_root
│
├── /data                   # Dataset files and preprocessing scripts
│   ├── preprocess.py
│   └── dataset.csv
│
├── /models                 # Model implementation files
│   ├── traditional_models.py
│   ├── deep_learning_models.py
│   └── utilities.py
│
├── /results                # Output results and analysis notebooks
│   ├── results_analysis.ipynb
│   └── performance_metrics.csv
│
└── README.md               # Project documentation
```

## Models

### Traditional Models

- **TF-IDF + Logistic Regression**: Applies TF-IDF vectorization followed by logistic regression for classification.
- **Word2Vec + Logistic Regression**: Utilizes Word2Vec for embedding text data, then applies logistic regression.

### Deep Learning Models

- **LSTM (Long Short-Term Memory)**: A type of recurrent neural network used to analyze text data sequences.
- **BERT (Bidirectional Encoder Representations from Transformers)**: Utilizes the pre-trained BERT model to process text and perform classification.

## Data

The dataset consists of 13,144 restaurant reviews with multiple attributes, categorized for multi-class classification based on cuisine type. Data preprocessing and exploratory data analysis (EDA) scripts are provided to prepare the dataset for modeling.

## Key Accomplishments

- **Data Preparation**: Integrated data cleaning, preprocessing, and exploratory analysis to understand the dataset's characteristics.
- **Model Implementation and Tuning**: Developed and fine-tuned both traditional and deep learning models for the task.
- **Performance Evaluation**: Compared model performances, demonstrating that traditional models outperformed deep learning in this context.

## Installation and Usage

To replicate the findings or further develop the models, follow these steps:

1. Clone the repository.
2. Ensure Python 3.8+ is installed.
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run the preprocessing script to prepare the data:
   ```
   python data/preprocess.py
   ```
5. Execute model scripts to train and evaluate the models:
   ```
   python models/traditional_models.py
   python models/deep_learning_models.py
   ```

## Conclusion

This project highlighted the effectiveness of traditional machine learning models over deep learning when dealing with limited and biased datasets. The findings challenge the prevailing notion that deep learning is superior for all types of data and tasks, providing valuable insights into the importance of choosing the right model based on dataset characteristics.

## How to Contribute

Contributions are welcome! Please refer to the issues tracker on GitHub for current tasks, and submit pull requests with your proposed changes.
