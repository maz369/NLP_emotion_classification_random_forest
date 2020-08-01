# NLP_emotion_classification_random_forest
This repository contains jupyter notebook implementation for classifying plain text into 5 categories of neutral, happiness, worry, hate and anger. The data set includes 47288 tweets scrapped from twitter. 
The code has been tested on Python 3.7.1, Anaconda (4.7)

The concept of n-gram has been utilized and a random forest classifier has been trained for the classification. This implementation includes grid search for tuning hyperparameters.
This is an early implementation of a series of my work on text classification. Using n-gram is not the best available method but it can be a good starting point.

# Test
- Create a virtual environment with Anaconda:  conda create -n env_name python=3.7 (Python 3 is compatible with packages)
- Activate the environment: activate env_name
- Change directory to where you cloned the current files: cd ./where files are downloaded
- Install required libraries: pip install -r requirements.txt

# Future work
- Expand number of emotions
- Train models on other text features such as TF-IDF


# License
The code comes "AS IS" with no warranty of any kind. It can be used for any educational and research purpose. Feel free to modify and/or redistribute.
