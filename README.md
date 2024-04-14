# Fake News Analyser And Predictor

Our project is focused on creating a machine learning model that can accurately identify and categorize news articles from various news and social media platforms as either fake or legitimate. The spread of fake news can have significant negative impacts on individuals and society. To address this, we are developing and training a model using a wide-ranging dataset of news articles. We have employed four different methods to evaluate the performance of the model.

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **SVM Classifier**
5. **Naive Bayes Classifier**

## Project Overview

In today's digital era, the rapid spread of information across various online platforms has made fake news a major problem. Our project utilizes machine learning algorithms to automatically assess the authenticity of news articles, offering a crucial resource for fighting misinformation.

## Dataset

We are utilizing a labeled dataset that includes news articles and their respective classifications (true or false). This dataset is organized into two categories -
- True: Authentic news articles
- False: Fake or fabricated news articles

## Dependencies

Before running the code, make sure the following libraries and packages are installed:

- Python 3
- Scikit-learn
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Regular Expression

These dependencies can be installed using pip:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install sklearn
pip install seaborn 
pip install re 
```

## Usage

1. Clone this repository on local machine:

```bash
git git@github.com:mondalbidisha/Fake-New-Analyser-Predictor.git
```

2. Navigate to the project directory:

```bash
cd Fake-New-Analyser-Predictor
```

3. Execute the Jupyter Notebook associated with each classifier to train and test the models. 

4. The code will produce performance and evaluation metrics as well as provide a prediction as to whether manually entered news data is real or fake.

