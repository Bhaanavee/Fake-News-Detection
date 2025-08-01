# Fake News Detection

## Description

This project aims to **detect fake news articles using machine learning techniques**. It addresses the problem of **the spread of misinformation and its impact on society** by **analyzing the text content and metadata of news articles**. The system employs natural language processing (NLP) and machine learning algorithms to classify news articles as either fake or real. Key features include:

- **Text Analysis:** Utilizes techniques like TF-IDF, word embeddings, and sentiment analysis to extract relevant features from the article text.
- **Metadata Analysis:** Incorporates metadata such as author, publication date, and source credibility to enhance detection accuracy.
- **Machine Learning Models:** Implements various classification models, including Logistic Regression, Support Vector Machines (SVM), and ensemble methods like Random Forest, to identify fake news.
- **Evaluation Metrics:** Employs metrics such as precision, recall, F1-score, and accuracy to evaluate the performance of the models.

## File Structure

The project directory is organized as follows:

```
Fake News Detection/
├── README.md             # This file, providing an overview of the project
├── app.ipynb             # Jupyter Notebook for model training
├── app.py                # Streamlit app for fake news detection
├── Fake.csv              # Dataset of fake news articles
├── lr_model.jb           # Trained Logistic Regression model
├── requirements.txt      # List of required Python packages
├── True.csv              # Dataset of true news articles
└── vectorizer.jb         # TF-IDF vectorizer
```

## Installation

To get started, follow these steps:

1.  Clone the repository:
    ```bash
    git clone [**replace with your repository URL**]
    ```
2.  Navigate to the project directory:
    ```bash
    cd [**replace with your project directory name**]
    ```
3.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the fake news detection tool:

1.  **Train the model:** Run the `app.ipynb` notebook to train the Logistic Regression model and save the model and vectorizer.
2.  **Run the Streamlit app:**
    ```bash
    streamlit run app.py
    ```
3.  Enter a news article in the text area and click "Check News" to see if it's predicted as fake or real.

## Contributing

We welcome contributions to this project! To contribute:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with clear, concise messages.
4.  Submit a pull request.


