# Russia-Ukraine-Sentimental-Analysis

Russia Versus Ukraine - Tweets Sentiments Exploratory Data Analysis using Python.

1. The dataset contains tweets regarding Russia and Ukraine from 21st February till date.
2. An Exploratory Data Analysis is performed from twitter data over Russia and Ukraine war.
3. Categorized the tweets into positive, negative an neutral sentiments using TextBlob s

**TextBlob** is a python library for Natural Language Processing (NLP).TextBlob actively used **Natural Language ToolKit (NLTK)** to achieve its tasks. NLTK is a library which gives an easy access to a lot of lexical resources and allows users to work with categorization, classification and many other tasks. TextBlob is a simple library which supports complex analysis and operations on textual data.

TextBlob returns **polarity** and **subjectivity** of a sentence. 

**Polarity** is a float value within the range **[-1.0 to 1.0]** where 0 indicates neutral, +1 indicates a very positive sentiment and -1 represents a very negative sentiment.
**Subjectivity** is a float value within the range **[0.0 to 1.0]** where 0.0 is very objective and 1.0 is very subjective. Subjective sentence expresses some personal feelings, views, beliefs, opinions, allegations, desires, beliefs, suspicions, and speculations where as Objective sentences are factual.

**Subjectivity quantifies the amount of personal opinion and factual information contained in the text**. The higher subjectivity means that the text contains personal opinion rather than factual information. TextBlob has one more parameter — intensity. TextBlob calculates subjectivity by looking at the ‘intensity’. Intensity determines if a word modifies the next word. For English, adverbs are used as modifiers (‘very good’).


                    ![image](https://user-images.githubusercontent.com/81230333/159703090-7a033c76-37eb-4343-a1dd-515fb7348d8d.png)


