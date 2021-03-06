## TextSimilarity

## Overview

This project is to estimate the similarities between the texts and get top n most similar text with similarity value. 
To get the features of the text, Gensim, NLTK, Spacy, libraries are used and scikit-learn library is used for the 
estimation of the similarity. 
Also, a pre-trained model which is part of a model that is trained on 100 billion words from the Google News Dataset is 
used for Natural Language Processing.

## Structure

- src

    The main source code for pre processing the text, extraction of their features.
    
- utils

    * The pre-trained model for NLP
    * The source code for management of the folders and files in this project
    
- app

    The main execution file

- requirements

    All the dependencies for this project
    
- settings

    Several settings including the input excel path, threshold value, top n number. 

## Installation

- Environment

    Ubuntu 18.04, Windows 10, Python 3.6

- Dependency Installation

    Please go ahead to this project directory and run the following commands in the terminal
    ```
        pip3 install -r requirements.txt
        python3 -m spacy download en_core_web_sm
        python3 -m nltk.downloader all
    ```
 
## Execution

- Please run the following command in the terminal

    ```
        python3 app.py
    ```
