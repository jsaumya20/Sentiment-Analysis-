# Sentiment-Analysis-
Performing sentiment analysis of the google play store app reviews. 

Scripting the steps we plan to take toward our project.
 
•Initially, the google play store app review dataset will be used for performing the sentiment analysis.

•The google play store app review folder contains 35 CSV files of various apps with information about the apps' comments. 
During the project the focus will be on performing the following activities:

•Clean the dataset using various Data cleaning techniques like : 
    •Select relevant data 
    •Handle missing/invalid data 
    •Handle outliers 
    •De-duplicate data
    •Correct date formats 
    •Merge data using 1-to-1 and 1-to-many mapping

•Perform Descriptive and Exploratory data analysis i.e. A graphical representation of the data which will give a sense of all the features within the dataset. 

•Perform Text mining on the data by deploying the following techniques:                                
## Functions for Preprocessing¶

### Expanding Contractions¶

Contractions are shortened version of words or syllables. They exist in either written or spoken forms. Shortened versions of existing words are created by removing specific letters and sounds. In case of English contractions, they are often created by removing one of the vowels from the word.

By nature, contractions do pose a problem for NLP and text analytics because, to start with, we have a special apostrophe character in the word. Ideally, we can have a proper mapping for contractions and their corresponding expansions and then use it to expand all the contractions in our text.

### Removing Special Characters¶

One important task in text normalization involves removing unnecessary and special characters. These may be special symbols or even punctuation that occurs in sentences. This step is often performed before or after tokenization. The main reason for doing so is because often punctuation or special characters do not have much significance when we analyze the text and utilize it for extracting features or information based on NLP and ML.

### Tokenizing Text¶

Tokenization can be defined as the process of breaking down or splitting textual data into smaller meaningful components called tokens.

Sentence tokenization is the process of splitting a text corpus into sentences that act as the first level of tokens which the corpus is comprised of. This is also known as sentence segmentation , because we try to segment the text into meaningful sentences.

Word tokenization is the process of splitting or segmenting sentences into their constituent words. A sentence is a collection of words, and with tokenization we essentially split a sentence into a list of words that can be used to reconstruct the sentence.

### Removing Stopwords¶

Stopwords are words that have little or no significance. They are usually removed from text during processing so as to retain words having maximum significance and context. Stopwords are usually words that end up occurring the most if you aggregated any corpus of text based on singular tokens and checked their frequencies. Words like a, the , me , and so on are stopwords.

### Correcting Words¶
One of the main challenges faced in text normalization is the presence of incorrect words in the text. The definition of incorrect here covers words that have spelling mistakes as well as words with several letters repeated that do not contribute much to its overall significance.

#### Correcting Repeating Characters

#### Correcting Spellings

#### Lemmatization¶

The process of lemmatization is to remove word affixes to get to a base form of the word. The base form is also known as the root word, or the lemma, will always be present in the dictionary.

Perform Sentiment analysis, which includes the following steps:                                                    
 
 •Feature Extraction 
 
 •Data Preprocessing 
 
 •Machine learning models 
 
 •Building Bag of Words Model.

Providing recommendations for the apps based on the finding.

