# RNN From Scratch – GK Question Answering

This directory contains the Jupyter Notebook implementation of a simple Recurrent Neural Network (RNN) for a General Knowledge (GK) Question Answering task using PyTorch.

##  Repository Structure

```text
RNN-From-Scratch-GK-QnA/
│
├── data/
│   ├── README.md
│   └── gk_qna_dataset.csv
│
├── docs/
│   └── Project documentation and architecture PDFs
│
├── notebooks/
│   ├── README.md
│   └── RNN-From-Scratch-GK-QnA.ipynb
│
├── .gitignore
├── LICENSE
└── requirements.txt
```

##  Notebook

| Notebook | Description |
|---|---|
| `RNN-From-Scratch-GK-QnA.ipynb` | Step-by-step implementation of a simple RNN-based question-answering model. |

##  Project Overview

The main objective is to understand how a Recurrent Neural Network works with text data and how to build a basic question-answering model using PyTorch.

##  Implementation Steps

1. **Data Loading** – Load the GK question-answer dataset using Pandas.
2. **Text Tokenization** – Convert text into tokens using Python Regular Expressions.
3. **Vocabulary Building** – Create a vocabulary from questions and answers.
4. **Text to Indices** – Convert text tokens into numerical representations.
5. **Dataset & DataLoader** – Prepare custom PyTorch Dataset and DataLoader.
6. **RNN Architecture** – Build a simple RNN model using PyTorch.
7. **Model Training** – Train the model using CrossEntropyLoss and Adam optimizer.
8. **Prediction** – Test the trained model with sample GK questions.

##  Model Architecture

The model consists of three main components:

- **Embedding Layer:** Converts word indices into dense vector representations.
- **RNN Layer:** Processes sequential input and extracts contextual information.
- **Fully Connected Layer:** Maps the final hidden state to vocabulary-sized output scores.

##  Technologies Used

- Python
- PyTorch
- Pandas
- Regular Expressions (re)
- Google Colab
- Jupyter Notebook

##  How to Run

1. Open the notebook using Google Colab.
2. Upload or mount the GK Q&A dataset.
3. Update the dataset file path if necessary.
4. Run all cells sequentially.
5. Train the model and test predictions.

##  Dataset

The dataset contains General Knowledge questions and their corresponding answers.

Dataset location: `data/gk_qna_dataset.csv`

##  Learning Outcomes

- Understanding text preprocessing and tokenization.
- Building a vocabulary for NLP tasks.
- Converting text into numerical representations.
- Implementing a custom PyTorch Dataset.
- Understanding basic RNN architecture.
- Training and testing a simple RNN model.

---

**Note:** This is an educational implementation for learning the fundamentals of RNNs and NLP. The current model predicts the first answer token rather than generating a complete answer.

**Author:** Tanzim Ahamed  
**GitHub:** [@tanzimahamed](https://github.com/tanzimahamed)
