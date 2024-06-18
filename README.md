# Persian Movies Genre Classification using NLP

## Overview

This project aims to familiarize you with the basics of Natural Language Processing (NLP) and solve a real-world text classification problem using transformer-based language models. We utilize a dataset of Persian movies, referred to as `persianmovies.csv`, which is accessible in the project documentation.

## Features

1. **Data Preprocessing**
2. **Statistical Description**
3. **Data Visualization**
4. **Genre Analysis**
5. **Time-based Analysis**
6. **Rating Analysis**
7. **Correlation and Multivariate Analysis**
8. **Outlier Detection**
9. **Data Balancing**

## Project Description

In this project, we aim to get acquainted with the fundamentals of NLP and solve a text classification problem using transformer-based language models (LM). The dataset used in this project consists of Persian movies, providing brief descriptions and features such as genre and production year in both Persian and English.

### Steps and Methods

1. **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
2. **Statistical Description**: Summarizing the dataset's key statistics.
3. **Data Visualization**: Visualizing data for better understanding and insights.
4. **Genre Analysis**: Analyzing the genres of movies in the dataset.
5. **Time-based Analysis**: Investigating trends and patterns over time.
6. **Rating Analysis**: Examining the ratings of the movies.
7. **Correlation and Multivariate Analysis**: Exploring relationships between multiple variables.
8. **Outlier Detection**: Identifying and handling outliers in the dataset.
9. **Data Balancing**: Ensuring a balanced dataset for better model performance.

### Model Training

The project involves training a BERT-based model for genre classification. The model's input is a summary of a movie, and the output is a classification among the existing genres. The process includes:

1. **Representation**: The language model processes the input and transforms it into a suitable representation.
2. **Classification**: A fully connected layer (fully connected head) is used for classification.

### Methodology

We employ various methodologies to achieve this, primarily focusing on fine-tuning a pre-trained BERT model end-to-end. This involves:

- Fine-tuning all the weights of the BERT model along with the classification head (CLS) layer.
- Ensuring the model is adequately trained and updated with the dataset provided.

## Usage

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/persian-movies-genre-classification.git
    ```
2. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```
3. **Run the Jupyter Notebook**:
    Open the Jupyter Notebook and follow the instructions to preprocess data, visualize it, and train the model.

## Dataset

The dataset `persianmovies.csv` includes Persian movies with brief descriptions and features such as genre and production year. It is bilingual, containing both Persian and English information.

## Results

The model's performance will be evaluated based on its accuracy in classifying movie genres. Various evaluation metrics will be used to ensure the model's robustness and reliability.

## Contributing

Feel free to submit pull requests or open issues if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

This project is part of my ongoing efforts to explore and contribute to the field of NLP and machine learning. Thank you for your interest!
