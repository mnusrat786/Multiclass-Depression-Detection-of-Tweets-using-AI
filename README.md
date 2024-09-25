# Master Thesis

# Multiclass Depression Detection of Tweets using AI
Depression is a significant issue nowaday. According to the World Health Organization (WHO) in 2023, over 280 million individuals are grappling with depression. This is a huge number if not taken seriously these numbers will increase rapidly. About 4.89 billion individuals are social media users. People express their feelings and emotions on platforms like Twitter, Facebook, Reddit, Instagram, etc. These platforms contain valuable information which can be used for research purposes. Considerable research has been conducted across various social media platforms. However, certain limitations persist in these endeavors. Particularly, previous studies were only focused on detecting depression and the intensity of depression in tweets. Also, there existed inaccuracies in dataset labeling. In this research work, five types of depression (Bipolar, major, psychotic, atypical, and postpartum) were predicted using tweets from the Twitter database based on lexicon labeling. Explainable AI was used to provide reasoning by highlighting the parts of tweets that represent that type of depression. Bidirectional Encoder Representations from Transformers (BERT) was used for feature extraction and training. Machine learning and deep learning methodologies were used to train the model. BERT gave the most promising results, achieving an overall accuracy of 0.96

# Pipeline

![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/073535a3-905b-4997-a6a9-da3ee88f1f17)


# Dataset
The dataset is available for research purposes. You can email me at osamanusrat786@gmail.com to request dataset access.

There are 14,317 tweets and six classes in the dataset. <br>

• Bipolar depression  <br>
• Psychotic depression  <br>
• Atypical depression <br>
• Postpartum depression <br>
• Major depressive disorder <br>
• No Depression <br>
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/0c02cab1-d7cc-4dce-a43f-8ff676187aae)

# Experimentation
Three Machine Learning Algorithms (Support Vector Machine, Random Forest, and Naive Bayes) were used in detecting depression on the dataset to get an estimate of which one of them gave better results.
## Depression Detection Using Support Vector Machine
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/f260b51e-84ef-4774-bce4-6cccf61ea15b)
## Depression Detection Using Random Forest
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/1e907016-a2e2-4c5e-b953-aed321b8a75d)
## Depression Detection Using Naive Bayes
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/02b6e85b-90bc-4052-ac1b-02c9b15bf82f)
## Comparison of Machine Learning Classifiers
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/d0ddac07-7fbd-452a-bb1b-d15d91548bf3)

## Results Using Deep Learning
Various deep learning models, including CNN, LSTM, and BERT, were employed to assess their performance on the
dataset.

## Depression Detection Using Convolutional Neural Networks (CNNs)
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/2a7be19a-9ad6-40c1-ad73-d01edf79a672)

## Depression Detection Using LSTM
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/501ddac0-16ac-442d-a2bd-57770efc206d)

## Depression Detection Using BERT
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/8373af7e-bf78-4135-88df-d56fd12ee74f)

## Comparison of Deep Learning Classifiers
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/1b493f7e-9a7c-4121-b414-e13cb8175779)

# Explainable AI
Explainable Artificial Intelligence, also known as XAI, is used so that the model also tells us on what basis it made
a certain decision. In other words, designing AI systems in such a way that they also explain their decision-making
process to humans. In sentiment analysis, explainable AI helps to know what features or words in a sentence make a
classification decision. This is done by highlighting the text in the sentence. In Python, two libraries, LIME and SHAP,
are used for XAI purposes. <br>
In the research context, XAI helps if a machine learning and deep learning model has predicted that a certain tweet
contains a certain type of depression. Then, it also explains why it made that decision. It highlights the text in the tweet,
saying that the model made this classification decision due to the highlighted word or words. <br>
# Result of Explainability
## Postpartum Depression
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/72df4f3a-5050-4133-84ad-b0fbc6916ea0)

## Atypical Depression 
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/6b8b872e-449f-4a75-a873-14486b72e85e)

## Psychotic Depression
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/c0978aac-821e-465c-9155-37ca3dab71ba)

## Major Depression
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/87e9a9b2-10a4-4692-b83c-3824057834d2)

## Bipolar Depression
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/aa0d024d-c88d-441b-9f7f-af996bdfc2c9)

## No Depression
![image](https://github.com/mnusrat786/Multiclass-Depression-Detection-of-Tweets-using-AI/assets/45511078/d826b6fb-4e94-4018-b071-ca829490dbc5)




