# Text Classification Model

#Overview
This project is a Natural Language Processing (NLP) application built to classify text documents into predefined categories. It uses TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction and a Multinomial Naive Bayes classifier to predict the topic of a given text.

The model is trained on the 20 Newsgroups dataset and evaluates performance using standard metrics like Precision, Recall, and F1-score, visualized via a Confusion Matrix.

#Features
-Text Preprocessing & Vectorization:Converts raw text into numerical vectors using TF-IDF.
-Multi-class Classification: Categorizes text into 4 distinct topics:
    * soc.religion.christian
    * sci.space
    * comp.graphics
    * rec.sport.hockey
-Model Evaluation: Generates a detailed classification report (Precision, Recall, F1-Score).
-Visualization: Plots a Confusion Matrix heatmap to visualize model performance.
-Real-time Prediction: Allows users to input custom sentences and get immediate classification predictions.

#Tech Stack
-Language: Python 3.x
-Libraries:
    *scikit-learn (Model building and metrics)
    * numpy (Data handling)
    * matplotlib & seaborn (Visualization)
