## Introduction to Text Mining with DH-Lab with apps

Keypoints:
- DH-Lab has made web-based apps for a simpler introduction to text mining the National Library's collection. 
- The apps are built on top of the DH-Lab API, using Streamlit, a free and open-source app framework in Python. 
- Among the apps are tools to search for concordances, collocations, N-gram and word frequencies, Named Entity Recognition (NER) & Part-of-Speech (POS) tagging, and Topic Modeling.

To use an app to text mine the National Library’s digitized collections:

- Go to the app page at [DH-Lab](https://www.nb.no/dh-lab/) and select the app for the type of text mining you want to do. 
- You first need to build a corpus using the corpus app. 
- You can then drag and drop the corpus you build to the app for the type of text mining you want to do.

## Named Entity Recognition (NER)

Named Entity Recognition (NER) tries to find out whether a word is a named entity (NE) or not. Named entities are definite noun phrases that refer to specific types of individuals, such as organizations, persons, dates, and so on. Entity recognition is often performed using chunkers, and part-of-speech (POS) tags are often a very important feature when searching for chunks. NLTK provides a classifier that has already been trained to recognize and tag named entities; you can read more about it in the [NLTK textbook](https://www.nltk.org/book/ch07.html#named_entity_recognition_index_term). 

DH-Lab uses spaCy instead of NLTK in its [app for NER](https://dh.nb.no/apps/navn-og-steder/). DH-Lab also offers [example Python code in Jupyter Notebook](https://nationallibraryofnorway.github.io/digital_tekstanalyse/tutorial/3.0.ner_og_pos.html) for how to do NER and POS analysis with the spaCy models in the National Library's digitized collections. spaCy is an open-source software library for advanced natural language processing, written in the programming languages Python and Cython. Unlike NLTK, which is widely used for teaching and research, spaCy focuses on providing software for production usage and is popular among app developers.

[Index](https://ang-uio.github.io/Textmining/)
