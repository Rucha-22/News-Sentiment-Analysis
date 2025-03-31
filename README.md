# *News-Sentiment-Analysis*
##News Classification Project
Course: NLP (Semester 6) - Pillai College of Engineering

###Project Overview:
This project is part of the Natural Language Processing (NLP) course for Semester 6 students at Pillai College of Engineering. The project focuses on Sentiment analysis of news, where we apply various Machine Learning (ML), Deep Learning (DL), and Language Models to identify the sentiment of news articles into predefined categories. This project involves exploring techniques like text preprocessing, feature extraction, model training, and evaluating the models for their effectiveness in identifying the news sentiment.
You can learn more about the college by visiting the official website of Pillai College of Engineering.

🔗 You can learn more about the college by visiting the [official website of Pillai College of Engineering](https://www.pce.ac.in).
##Acknowledgements:
We would like to express our sincere gratitude to the following individuals:

Theory Faculty:

1.   Dr.Dhiraj Amin
2.   Dr.Sharvari Govilkar

Lab Faculty:
1. Dr.Dhiraj Amin
2. Prof.Neha Ashok
3. Dr.Shubhangi Chavan
Their guidance and support have been invaluable throughout this project.

#*Project Title*: Sentiment analysis in news using Natural Language Processing

###*Project Abstract*:
The Sentiment analysis model processes the content of newsprint, which categorizes them as either positive, negative, or neutral using natural language processing (NLP) and machine learning techniques. It reads large volumes of text to detect the emotional impact that news has on its readers and society. The framework consists of text preprocessing (tokenization, stop-word removal and lemmatization), aggregation of sentiment through several classifiers and data collection from across multiple sources. The goal of this project is to improve information consumption, improve decision-making, and enrich our understanding of news sentiment during the digital age.

###Algorithms Used:
1. Machine Learning Algorithms:
2. Logistic Regression
3. XGBoost
4. Catboost 

###Deep Learning Algorithms:
1. Convolutional Neural Networks (CNN)
2. BiDirectional Long Short-Term Memory(BiLSTM)
3. Long Short-Term Memory (LSTM)
4. CNN and LSTM

###Language Models:
1. RoBERTa
2. DistilBERT 
Comparative Analysis:
The comparative analysis of different models highlights their effectiveness in classifying news articles into the correct category. The following table summarizes the accuracy of the models tested:

## Model Performance Comparison

| Model                                       | Accuracy |
|---------------------------------------------|----------|
| CatBoost + FastText                         | 0.7443   |
| XGBoost + BoW                               | 0.8129   |
| Logistic Regression + Combined Features     | 0.8000   |
| CNN + Word2Vec                              | 0.5536   |
| LSTM + Word2Vec                             | 0.4521   |
| CNN-BiLSTM + Word2Vec                       | 0.5333   |
| BiLSTM + Word2Vec                           | 0.4405   |
| DistilBERT                                  | 0.7777   |
| RoBERTa                                     | 0.6620   |

### Notes:
- *XGBoost + BoW* achieved the highest accuracy (0.8129).
- *Transformer-based models (DistilBERT, RoBERTa)* performed well, but RoBERTa underperformed compared to DistilBERT.
- *Deep learning models using Word2Vec (CNN, LSTM, BiLSTM)* had significantly lower accuracy.
- *Logistic Regression with combined features* performed competitively, suggesting feature engineering played a crucial role.

##*Conclusion:*
This News sentiment analysis project demonstrates the potential of Machine Learning, Deep Learning, and Language Models for text classification tasks, particularly for identifying news sentiment. The comparative analysis reveals that XGBoost, a machine learning-based model, outperforms transformer methods and deep learning models in terms of accuracy. By employing various algorithms, we gain insights into the strengths and weaknesses of each model, allowing us to choose the most suitable approach for news classification.

This version tailors the description to focus on News Sentiment analysis while maintaining the structure and content related to the NLP project. It includes relevant details on algorithms used, a comparative analysis table, and the necessary acknowledgments for faculty members involved in the course.
