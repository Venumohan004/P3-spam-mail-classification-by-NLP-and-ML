# P3-Spam-Email-Classification-by-NLP-and-ML

<h1>Overview Of The Project </h1>

<p>The majority of the correspondence and exchange in all business sectors take place through Emails. As the rate of exchange of information via emails is increasing exponentially, the amount of unsolicited bulk mail or Spam. These Emails are sent for a number of reasons: Extracting confidential information from individuals, promotion of adult content and marketing/advertising of products and services. Thus, keeping this mind, it is of paramount importance to build a comprehensive system for Spam Classification based on semantics based text classification using NLP and URL based filtering. Various Machine Learning algorithms have been surveyed and the objective is to create a model with high performance and efficiency<br>
As the usage of mobile phones increased, the use of Short Message Service increased significantly. Due to the lower costs of text messages, people started using it for promotional purposes and unethical activities. This resulted in the ratio of spam messages increasing exponentially and thereby loss of personal and financial data. To prevent data loss, it is crucial to detect spam messages as quick as possible. Thus, the research aims to classify spam messages not only efficiently but also with low latency. Different machine learning models like XGBoost, LightGBM, Bernoulli Naïve Bayes that are proven to be very fast with low time complexity have been implemented in the research. The length of the messages was taken as an additional feature, and the features were extracted using Unigram, Bigram and TF-IDF matrix. Chi Square feature selection was implemented to further reduce the space complexity. The results showcased that Bernoulli Naïve Bayes followed by LightGBM with the TF IDF matrix generated the highest accuracy of 96.5% in 0.157 seconds and 95.4% in 1.708 seconds respectively. Keywords: Spam SMS, Text Classification, Natural Language Processing, Machine Learning, Bernoulli Naïve Bayes, LightGBM, XGBoost </p>

# SafeMailAI

SafeMailAI is a powerful email classification tool that leverages NLP and machine learning to protect your inbox from spam. With an intuitive interface built on Streamlit, it accurately identifies and filters spam, ensuring a secure and clutter-free email experience.


## Features

- **Email Classification**: Enter an email and classify it as either Spam or Not Spam.
- **Model Performance**: View accuracy, confusion matrix, and classification report on the dataset.
- **User-Friendly Interface**: The result is displayed with a colored background to clearly indicate whether an email is Spam (red) or Not Spam (green).

## Installations 
### 1. Clone the Repository
```bash
git clone https://github.com/Venumohan004/P3-spam-mail-classification-by-NLP-and-ML/tree/main

```





<h2>How To Executed The Project</h2>
<h3>Step by step process </h3>

1.Data Collection: Gather a labeled dataset of emails.<br>
2.Preprocessing: Clean and process the text (tokenization, stopword removal, etc.).<br>
3.Feature Extraction: Convert text into numerical features.<br>
4.Model Training: Use a machine learning model like Naive Bayes.<br>
5.Evaluation: Measure model performance using metrics like accuracy and F1-score.<br>
6.Deployment: Integrate the model into an email system for real-time classification.<br>
By following these steps, you can successfully classify spam and non-spam emails using NLP and machine learning techniques<br>

# Happy to Learning and coding 😊
