# Sentiment Analysis Approach for Reputation Evaluation

### Objective
* Evaluate and Compare the selected sentiment classification techniques used to evaluate brand reviews.
* Findings are presented to make informative decisions regarding the adoption of classification techniques.

### Proposed Methodology
* Dataset containing 400,000 reviews of unlocked mobile phones sold on Amazon was selected.
* Four approaches (lexicon-based, machine learning, hybrid and LSTM) were implemented to identify the underlying sentiment.
* Model evaluation metrics were utilised for comparative analysis.

### Programming Language and Software Tools
* PyCharm by JetBrains
* Python
* Scikit-Learn Library

### Results
* Accuracy of Hybrid approach was the highest, giving 91.05% of correctly predicted observation.
* Precision score of Lexicon-based approach was the lowest with 79.0% of correctly predicted positive observations.
* F1 score of Hybrid approach was the highest, presenting with 85.2% of harmonic mean between precision and recall. 
* The positive sentiment label in Apple and BlackBerry mobile reviews were higher, compared to the negative and neutral sentiment labels.

### Conclusions
* Hybrid approach and LSTM(Wor-to-Vec) to sentiment analysis can effectively be used to evaluate brand reviews that benefit businesses.
* Underlying sentiment of brand reviews can be evaluated with the use of sentiment classification techniques. 
* Slang and emoticons handling may be implemented to improve results of sentiment analysis.
