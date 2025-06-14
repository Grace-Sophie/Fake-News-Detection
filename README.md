## Fake-News-Detection

### Overview

This project, completed as part of a university assignment, aimed to detect whether text was real or fake news. This was done through Natural Language Processing. A model was then trained using Passive Agressive classifiers. Each model is trained multiple times with a set of different parameters using a grid search to optimize the model for the best outcome and measure is taken to ensure the models do not overfit or underfit the data. 

### Project Implementation

1. **Data Preprocessing and Cleaning:**  
   The corpus collected from the World Wide Web is preprocessed before being used as an input for training the models. The articles’ unwanted variables such as authors, date posted, URL, and category are filtered out. Articles with no body text or having less than 20 words in the article body are also removed. Multicolumn articles are transformed into single column articles for uniformity of format and structure. These operations are performed on all the datasets to achieve consistency of format and structure.

2. **Exploratory Data Analysis (EDA):**  
 The EDA phase included generating meta-features like the number of words in texts and selected texts, which provided insights into the data's characteristics.

3. **Feature Engineering:**  
   This involved the extraction of the linguistic features. Linguistic features involved certain textual characteristics converted into a numerical form such that they can be used as an input for the training models. These features include percentage of words implying positive or negative emotions; percentage of stop words; punctuation; function words; informal language; and percentage of certain grammar used in sentences such as adjectives, preposition, and verbs. As all of the features extracted are numerical values, no encoding is required for categorical variables. 

4. **Model Training:**  
   The input features are used to train the different machine learning models. Each dataset is divided into training and testing set with a 80/20 split, respectively. The articles are shuffled to ensure a fair allocation of fake and true articles in training and tests instances.


### Problem Addressed

The problem tackled was the identification of key phrases within text news that increase chances of the news being real or fake. Our ability to take a decision relies mostly on the type of information we consume making this a crucial and necessary task.


### Conclusion

Through meticulous data analysis and the application of NLP techniques, the project highlights the potential of machine learning and NLP in determining the authenticity of information.
