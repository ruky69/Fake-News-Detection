# Fake-News-Detection
## WHAT IS FAKE NEWS?
Fake news contains pieces of news that may be hoaxes and are often spread through different online media outlet like Twitter, Instagram, Facebook, WhatsApp etc. The aim of spreading fake news is usually done to impose certain ideas with various agendas attached to the idea behind fake news. These news items that contain exaggerated and/or false claims could end up being viralized by online algorithms, which may put users into a filter bubble.

## AIM
The aim of this project is to build machine learning models that would be able to predict most accurately when an information passed out is fake news.

**The Notebooks accomplishes the following:**
- Text cleaning. The steps for cleaning of text from the data involves:
    1. Removing punctuations.
    2. Converting text to tokens(words).
    3. Applying lemmatization (the conversion of words to its base form). Example: stays, staying, stayed ---> stay (base form).
- Creating and transforming the text to TF-IDF vectors.
- Three machine learning models were used for predicting fake news: 
    1. PassiveAggressiveClassifier
    2. LogisticRegression
    3. MultinomialNB
- Evaluate each model based on their accuracy score, classification report and confusion matrix. 

Please refer to the notebooks for details on the steps carried out.
