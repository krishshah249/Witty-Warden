# Sarcasm Detection

This project aims to detect sarcasm in textual data using machine learning and natural language processing techniques. Sarcasm detection has various applications in sentiment analysis, social media monitoring, and customer feedback analysis.

## Overview

Sarcasm is a form of verbal irony often characterized by using words to convey the opposite of their literal meaning, typically in a mocking or humorous manner. Detecting sarcasm in text can be challenging due to its context-dependent nature and the use of figurative language.
This project focuses on developing a machine learning model capable of identifying sarcasm in textual data. The model is trained on a dataset containing examples of sarcastic and non-sarcastic sentences to learn patterns and features indicative of sarcasm.

## Dataset

The dataset used in this project is the News Headline for Sarcasm Detection dataset from Kaggle. It contains News Headline and article link labeled as sarcastic or non-sarcastic. The data is available at [Dataset](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection).

## Classification methods used:

- **Multinomial Naive Bayes**
- **Logistic Regression**
- **Support Vector Machine**
- **Random Forest**

## Model Optimization methods used:

- **Grid Search**

## Usage

To use this project:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/krishshah249/Witty-Warden.git
    ```

2. Navigate to the cloned repository:

    ```bash
    cd Witty-Warden
    ```

3. Run the provided Jupyter notebook to train and evaluate the sarcasm detection model.

## Explorative Data Analysis

#### Source Column data distribution

![source][0]

#### Frequency of the occuring words

![frequency][1]

#### Removing stop words of the non sarcastic occuring words and generating word cloud

![stop_word][2]

#### Removing stop words of the sarcastic occuring words and generating word cloud

![stop_word_sarcastic][3]

#### Comparision of the length of sarcastic and non sarcastic headlines

![length][4]

## Model Evaluation

The sarcasm detection model is evaluated based on various performance metrics such as accuracy, precision, recall, and F1-score. The evaluation results are presented in the notebook/script and can help assess the model's effectiveness in detecting sarcasm.

#### The ROC - AUC curve for the above mentioned algorithms can be seen from the chart shown below

![ROC_AUC][5]

#### The confusion matrix for the Logistic Regression can be seen from the chart shown below

![LR_confusion][6]

#### The confusion matrix for the Multinomial Naive Bayes can be seen from the chart shown below

![NB_confusion][7]

#### The confusion matrix for the Random Forest can be seen from the chart shown below

![RF_confusion][8]

## Contributing

Contributions to this project are welcome! If you have ideas for improvements, new features, or bug fixes, feel free to open an issue or submit a pull request.


[0]: images/source.png
[1]: images/frequency.png
[2]: images/stop_word.png
[3]: images/stop_word_sarcastic.png
[4]: images/length.png
[5]: images/ROC_AUC.png
[6]: images/LR_confusion.png
[7]: images/NB_confusion.png
[8]: images/RF_confusion.png