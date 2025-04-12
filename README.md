# Sentiment Analysis on IMDb Movie Reviews

This project focuses on **Sentiment Analysis** of IMDb movie reviews using **Natural Language Processing (NLP)** techniques. The goal is to classify movie reviews as either **positive** or **negative** based on their content.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Overview

The sentiment analysis model uses IMDb movie reviews dataset to classify reviews into two categories: **positive** and **negative**. The project demonstrates the usage of **TF-IDF vectorization** and **Logistic Regression** as the primary methods for feature extraction and model training. The model is evaluated using metrics like **accuracy**, **precision**, **recall**, and **F1-score**.

### Key Features:
- **Preprocessing**: Text cleaning, tokenization, stopword removal, and lemmatization.
- **Vectorization**: **TF-IDF** (Term Frequency-Inverse Document Frequency) for feature extraction.
- **Modeling**: Logistic Regression for classification.
- **Evaluation**: Performance metrics for classification accuracy and precision.

## Technologies Used

- **Python 3.8+**
- **Libraries**:
  - `nltk` (for text preprocessing)
  - `sklearn` (for machine learning and model evaluation)
  - `pandas` (for data manipulation)
  - `matplotlib` (for visualization)
- **Machine Learning Algorithms**: Logistic Regression

## Data

The dataset used in this project comes from the **IMDb Movie Reviews** dataset, which contains labeled movie reviews, with each review classified as either **positive** or **negative**.

- **Training Data**: Contains 12,500 positive reviews and 12,500 negative reviews.
- **Testing Data**: Similarly balanced with 12,500 positive and 12,500 negative reviews.

The data is processed using **TF-IDF** vectorization to transform text data into numerical features suitable for machine learning.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/YousefAlaaAli/sentiment-analysis-imdb.git
    cd sentiment-analysis-imdb
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the sentiment analysis:

1. Make sure all dependencies are installed.
2. Run the Python script to train and evaluate the model:
    ```bash
    python sentiment_analysis.py
    ```

After running the script, you will get the model's performance metrics (accuracy, precision, recall, and F1-score).

## Model Evaluation

The model achieves the following performance on the test set:

- **Accuracy**: 87.88%
- **Precision**: 0.88 (for both positive and negative classes)
- **Recall**: 0.88 (for both positive and negative classes)
- **F1-Score**: 0.88 (for both positive and negative classes)

This indicates that the model performs very well on both positive and negative reviews.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request if you have any improvements, fixes, or new features you'd like to add.

### Steps to contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
