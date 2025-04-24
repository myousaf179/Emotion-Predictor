# Emotion Prediction Project

This project is designed to predict emotions from text using a machine learning model. It utilizes a logistic regression algorithm trained on a dataset of emotional text inputs.

## Project Structure

```
emotion-prediction
├── src
│   ├── data
│   │   └── isear.csv          # Dataset used for training the emotion prediction model
│   ├── models
│   │   └── emotion_model.pkl   # Serialized model including the trained logistic regression model and vectorizer
│   ├── notebooks
│   │   └── Emotion_prediction_from_text.ipynb  # Jupyter notebook for loading data, training, and evaluating the model
│   └── utils
│       └── text_preprocessing.py  # Utility functions for text preprocessing
├── requirements.txt              # Python dependencies required to run the project
├── .gitignore                    # Files and directories to be ignored by Git
└── README.md                     # Documentation for the project
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd emotion-prediction
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook `src/notebooks/Emotion_prediction_from_text.ipynb` to run the code for training the model and making predictions.
2. You can also use the utility functions in `src/utils/text_preprocessing.py` for any additional text preprocessing needs.

