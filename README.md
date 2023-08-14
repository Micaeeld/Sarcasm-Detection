##### Use https://nbviewer.org to upload the file in case of errors
---

# Detecting Sarcasm in Sentences
This project aims to detect sarcasm in sentences using a data set in JSON format. The model uses the Natural Language Toolkit (NLTK) library and the Naive Bayes algorithm to classify sentences as sarcastic or not.

## Data set
The dataset used in this project is available at https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection. The file contains a set of sentences classified as sarcastic or non-sarcastic. The phrases are in JSON format and each object has the following structure:

source" : {
"article_link": string"https://www.huffingtonpost.com/entry/versace-black-code_us_5861fbefe4b0de3a08f600d5"
"headline" : string"former versace store clerk sues over secret 'black code' for minority shoppers"
"is_sarcastic": int 0
}

The value of the is_sarcastic key is an integer that indicates whether the sentence is sarcastic or not. The value 1 represents a sarcastic phrase and the value 0 represents a non-sarcastic phrase.

## Results
When you run the notebook, you will be able to see the model results for the test sentences. The model will provide a classification for each sentence as sarcastic or not sarcastic.

It is important to remember that detecting sarcasm in sentences is a difficult and often subjective task. This model was trained on a specific set of phrases and may not work well on other datasets. Therefore, it is recommended that you evaluate the template results carefully and verify that it fits your specific needs.

## Contribution
Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request.
a pull request.
