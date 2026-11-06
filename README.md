# Fake News Detection Using Machine Learning

## About the Project
Fake News Detection is a Machine Learning-based Python project that classifies news articles as Real News or Fake News using Natural Language Processing (NLP).

The project uses TF-IDF Vectorization to convert text into numerical features and Logistic Regression to classify news.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Machine Learning
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Logistic Regression

## Features
- Accepts news text from the user.
- Converts text into numerical features using TF-IDF.
- Uses a Logistic Regression classification model.
- Predicts whether the entered news is Real or Fake.
- Displays the prediction result.

## Project Workflow
1. Collect sample news data.
2. Create a dataset using Pandas.
3. Convert news text into numerical values using TF-IDF.
4. Train the Logistic Regression model.
5. Accept news input from the user.
6. Predict and display the result.

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/ShrishtyRanjan-ops/Fake-News-Detection.git
```

### 2. Navigate to the Project Folder
```bash
cd Fake-News-Detection
```

### 3. Install Required Libraries
```bash
pip install -r requirements.txt
```

### 4. Run the Project
```bash
python main.py
```

## Sample Output
```text
Enter News: Aliens have taken over the White House

Fake News
```

## Machine Learning Algorithm
Logistic Regression is used as the classification algorithm.

TF-IDF (Term Frequency-Inverse Document Frequency) is used for text feature extraction.

## Future Improvements
- Use a larger and reliable news dataset.
- Improve model accuracy through proper training and testing.
- Add a web-based user interface.
- Evaluate the model using accuracy, precision, recall and F1-score.

## Disclaimer
This project is an educational demonstration using a very small sample dataset. Its predictions are not reliable for verifying actual news or determining whether a real-world news article is true.

## Author
Shrishty Ranjan

## License
This project is available for educational purposes.
