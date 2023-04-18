## Introduction to Text Mining with DH-Lab Jupyter Notebooks with example Python code 

Keypoints:
- With the API from the DH-Lab you can text mine just about all of the National Library of Norway's digitized collection.
- The DH-Lab has prepared Python code in Jupyter Notebooks you can copy and adapt precisely as you want.
- There is example code to serach for concordances, collocations, N-gram and word frequencies, Named Entity Recognition (NER) & Part-of-Speech (POS) tagging, Topic Modelling, and Sentiment Analysis.

The [DH-Lab](https://www.nb.no/dh-lab/) at the National Library of Norway has written example code to text mine the National Library’s huge digitized collection, and it is developing web-based apps for a simpler introduction to text mining the National Library's collection. The code is written in Python and shared in Jupyter Notebook, and the apps are made using Streamlit, a free and open-source app framework in Python.

Access DH-Lab Apps and Notebooks at [nb.no/dh-lab](https://www.nb.no/dh-lab/).

To run code to text mine the National Library’s digitized collections:
- Download example notebook from DH-Lab. Begin witht the first before selecting notebook based on type of text mining.
- Download and install Anaconda. 
- Open Anaconda, launch Jupyter Notebook from Anaconda, and open the downloaded notebook. 
- Begin at the top of the downloaded notebook and follow the instructions. 
- Run all cells in the notebook.

## Sentiment Analysis

Also known as “opinion mining”, sentiment analysis describes automated methods to identify affective states in data sets. This is done through systematic selection of expressions of subjective opinions and emotional evaluations in the material. Sentiment analysis is popular in marketing, advertising and to examine the tone of political communication, public debate, social media as well as studies of plot and genre in literary corpora. 

Digital sentiment analysis uses word lists and data sets where words and expressions are given a score based on perceived emotional meaning in sentiment analysis of text data. NLTK comes with a [sentiment package](https://www.nltk.org/api/nltk.sentiment.html), and DataCamp has made a [NLTK Sentiment Analysis Tutorial for Beginners](https://www.datacamp.com/tutorial/text-analytics-beginners-nltk). 

Scientists at the University of Oslo participating in the project [Sentiment Analysis for Norwegian Text (SANT)](https://www.mn.uio.no/ifi/english/research/projects/sant/) have developed data sets for sentiment analysis in Norwegian, [NorSentLex](https://www.mn.uio.no/ifi/english/research/projects/sant/news/new-sant-resources.html), a Norwegian sentiment lexicon, indicating the prior positive or negative polarity of words. DH-Lab has written example code in Python using NorSentLex, to do a sentiment analysis of a newspaper corpus in the digitized collection of the National Library. See [example code shared in Jupyter Notebook](https://nationallibraryofnorway.github.io/digital_tekstanalyse/cookbook/4.0.sentiment_analysis_timeseries.html). 

[Index](https://ang-uio.github.io/Textmining/)
