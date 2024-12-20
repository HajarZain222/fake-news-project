Overview

This project focuses on detecting fake news using machine learning techniques. The dataset comprises articles labeled as either "fake" or "real," and the goal is to build a model that can accurately classify news articles based on their content.

Features

Dataset loading and preprocessing
Exploratory data analysis (EDA) of text data
Implementation of machine learning models for classification
Evaluation metrics to assess model performance

Installation

Clone the repository:
git clone https://github.com/HajarZain222/fake-news-project.git
cd fake-news-project

Install the required dependencies:
pip install -r requirements.txt

Dataset

The project uses two CSV files:

True.csv: Contains real news articles
Fake.csv: Contains fake news articles

Ensure these files are available in the project directory. The dataset should have the following columns:

title: The title of the article
text: The full text of the article
subject: The category/topic of the article
date: The publication date

Usage

Open the Jupyter notebook:
jupyter notebook fake-news-project.ipynb

Run the cells step by step to:
Load the dataset
Perform data cleaning and preprocessing
Train and evaluate the machine learning models

Requirements
Python 3.7+
pandas
numpy
scikit-learn
Jupyter Notebook

Install all dependencies using the requirements.txt file provided.

Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

The dataset was sourced from publicly available repositories of fake and real news articles.
Thanks to the open-source community for providing the tools and resources used in this project.

