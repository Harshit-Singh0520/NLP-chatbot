# Intermediate NLP Chatbot using Python and Machine Learning

An intent-based chatbot built using Python, Natural Language Processing (NLP), and Machine Learning. It uses TF-IDF vectorization and Logistic Regression to understand user queries and generate predefined responses based on predicted intents.

## Project Overview

This project is an intermediate-level NLP chatbot designed to recognize user intents and respond to common questions related to Python, Machine Learning, NLP, careers, and general conversations.

The chatbot uses text preprocessing and machine learning classification to identify the intent behind a user's message.

## Technologies Used

- Python
- Natural Language Processing (NLP)
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Pandas
- Jupyter Notebook

## Key Features

- Intent classification using Logistic Regression.
- Text vectorization using TF-IDF.
- Unigram and bigram feature extraction.
- Text normalization and preprocessing.
- Confidence-based fallback responses.
- Multiple predefined responses for each intent.
- Conversation history tracking.
- Model evaluation using accuracy and classification report.
- Interactive command-line chatbot.

## Supported Topics

The chatbot currently supports these intents:

1. Greeting
2. Goodbye
3. Thanks
4. Bot Identity
5. Help
6. Python
7. Machine Learning
8. Natural Language Processing
9. Project Ideas
10. Career Guidance
11. Working Hours

## Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project folder:

```bash
cd NLP-Chatbot
```

Install the required library:

```bash
pip install scikit-learn
```

## How to Run

Run the Python file:

```bash
python intermediate_nlp_chatbot.py
```

If you are using Jupyter Notebook:

```python
%run intermediate_nlp_chatbot.py
```

## Special Commands

| Command | Description |
|---|---|
| `/help` | Display available commands |
| `/history` | View conversation history |
| `/evaluate` | Display model evaluation |
| `/quit` | Exit the chatbot |

## Machine Learning Workflow

1. Prepare intent-based training data.
2. Normalize input text.
3. Convert text into numerical features using TF-IDF.
4. Train a Logistic Regression classifier.
5. Predict the intent of user queries.
6. Check prediction confidence.
7. Generate a predefined response based on the predicted intent.

## Model Evaluation

The project uses:

- Train-test split
- Accuracy score
- Classification report
- Precision
- Recall
- F1-score

## Project Limitations

- The chatbot responds only to intents included in its training data.
- It does not generate new answers like ChatGPT.
- Response quality depends on the examples provided during training.
- Unrecognized queries may receive a fallback response.

## Future Improvements

- Expand the training dataset.
- Add more intents and responses.
- Improve intent classification accuracy.
- Integrate a web-based user interface using Flask or Streamlit.
- Explore LLM and Generative AI integration.

## Author

Harshit Singh

**Project:** Intermediate NLP Chatbot using Python and Machine Learning
