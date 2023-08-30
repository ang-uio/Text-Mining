[Intro to Jupyter](episodes/02-jupyter-notebook.md)
[Python Fundamentals](episodes/03-python-basics.md)
[Tokenising Text](episodes/04-tokenising-text.md)
[Data Preprocessing](episodes/05-preprocessing-dataset.md)
[Concordances](episodes/06-concordances.md)
[Regular Expressions](episodes/07-regular-expression-search.md)
[Counting Tokens](episodes/08-counting-tokens.md)
[Frequency Distributions](episodes/09-frequency-distributions.md)
[Lexical Dispersion Plot](episodes/10-lexical-dispersion-plot.md)
[Plotting Frequency over Time](episodes/11-plotting-frequency-over-time.md)
[Collocations](episodes/12-collocations.md)
[Part-of-Speech-Tagging (POS)](episodes/13-part-of-speech-tagging-text.md)
[Named-Entity-Recognition (NER)](https://ang-uio.github.io/Textmining/episodes/16-textmine-dh-lab-app.html#named-entity-recognition-ner)
[Topic Modeling](https://ang-uio.github.io/Textmining/episodes/14-textmine-voyant.html#topic-modeling)
[Sentiment Analsysis](https://ang-uio.github.io/Textmining/episodes/15-textmine-dh-lab.html#sentiment-analysis)
[Python Day](python-day.md)
[Practice Review](episodes/review.md)
[About](episodes/01-textmining-intro.md)

## Welcome to this Introduction to Text Mining!

[What is text mining?](https://www.ub.uio.no/english/libraries/dsc/research-methods/text-mining/)

"Text Mining is the discovery by computer of new, previously unknown information, by automatically extracting information from different written resources... The difference between regular data mining and text mining is that in text mining the patterns are extracted from natural language text rather than from structured databases of facts." - [from What is Text Mining?](https://people.ischool.berkeley.edu/~hearst/text-mining.html) by [Marti Hearst](https://en.wikipedia.org/wiki/Marti_Hearst)

Why text mining? Automated search strategies can provide an overview of patterns and tendencies in large volumes of text. This may provide insight that would otherwise be difficult to achieve, time-consuming or both through conventional qualitative methods.

## Please consult the links and read the below:

[Types of text mining and digital analysis of text](https://www.ub.uio.no/english/libraries/dsc/research-methods/text-mining/text-mining-types.html)

[Tools and software bundles for text mining](https://www.ub.uio.no/english/libraries/dsc/research-methods/text-mining/tools-software-bundles.html)

Text mining requires readable big data. In this course, we will pay particular note to the value of platforms such as [NLTK](https://www.nltk.org/), a leading platform for building Python programs to work with human language data, and [DH-Lab](https://www.nb.no/dh-lab/), which facilitates text mining of the entire digitized collection of the National Library of Norway. 

More and more archives have their own tools to text mine their collections, with or without subscription. Some familiarity with programming is often necessary, typically in Python. Most of this course is therefore devoted to getting a fundamental competence of the Python programming langauge.

Learning a programming language is like learning any new language. It requires copying, repeating, using a dictionary, practicing, learning enough of the 'grammar' of the language to detect typos and mistakes.

A key in learning to master a programming language, is learning how to look things up. Therefore in this course you will become familiar with the practice of looking things up and becoming familiar with some of the most relevant ([textbooks](https://ang-uio.github.io/Textmining/#recommended-readings), [published tutorials](https://programminghistorian.org/en/lessons/?search=python), [online resources](https://github.com/sgsinclair/alta/blob/2eb10ab6787d032e317ce883fb0bc3427406333d/ipynb/Useful%20Resources.ipynb), and [forums](https://stackoverflow.com/)).

With a competence in Python, comes a deeper understanding of web applications for text mining, including [DH-Lab Tools](https://www.nb.no/dh-lab/) and [Voyant Tools](https://voyant-tools.org/docs/#!/guide/about) which this course will also introduce you to. 

> **Learning goals:**
> 
> - Get a fundamental understanding of how the Python program works (the math behind it with strings and loops etc.).
> 
> - Get a fundamental understanding for how Python code can be used to text mine.
>
> - Get a fundamental understanding for how the web applications from DH-Lab and Voyant can be used to text mine.
>
> - Get the fundamental competence required in Python and apps for text mining to define and conduct your own text mining project.

## Recommended and required readings:
Book Chapters: 
- [Natural Language Processing with Python: Analyzing Text with the Natural Language Toolkit](https://www.nltk.org/book/). The book is recommended as a whole. Required chapter readings are [1. Language Processing and Python](https://www.nltk.org/book/ch01.html), [2. Accessing Text Corpora and Lexical Resources](https://www.nltk.org/book/ch02.html), and [3. Processing Raw Text](https://www.nltk.org/book/ch03.html).
- [Humanities Data Analysis: Case Studies with Python](https://www.humanitiesdataanalysis.org/index.html). This book is also recommended as a whole. Required chapter readings are the sub chapters of DATA ANALYSIS ESSENTIALS, including the Introduction, Parsing and Manipulating Structured Data, and Exploring Texts using the Vector Space Model, see in particular ["What you should know"](https://www.humanitiesdataanalysis.org/introduction-cook-books/notebook.html#what-you-should-know)(on variables, strings, loops, lists, dictionaries, conditional expressions (if, elif, else), and reading files) and on [data formats](https://www.humanitiesdataanalysis.org/getting-data/notebook.html#plain-text) and [preprocesing](https://www.humanitiesdataanalysis.org/vector-space-model/notebook.html#text-preprocessing).

Articles:
- [A Beginner's Guide to Using Voyant for Digital Theme Analysis](https://hcommons.org/deposits/item/hc:49487/)
- [The Rise of Health. A Collocation Analysis of Conceptual Changes in News Discourse, 1950-2010](https://www-berghahnjournals-com.ezproxy.uio.no/view/journals/contributions/17/2/choc170202.xml) (text mining the National Library of Norway)

## Overview of workshop episodes:

- [Intro to Jupyter](episodes/02-jupyter-notebook.md)
- [Python Fundamentals](episodes/03-python-basics.md)
- [Tokenising Text](episodes/04-tokenising-text.md)
- [Data Preprocessing](episodes/05-preprocessing-dataset.md)
- [Concordances](episodes/06-concordances.md)
- [Regular Expressions](episodes/07-regular-expression-search.md)
- [Counting Tokens](episodes/08-counting-tokens.md)
- [Frequency Distributions](episodes/09-frequency-distributions.md)
- [Lexical Dispersion Plot](episodes/10-lexical-dispersion-plot.md)
- [Plotting Frequency over Time](episodes/11-plotting-frequency-over-time.md)
- [Collocations](episodes/12-collocations.md)
- [Part-of-Speech-Tagging (POS)](episodes/13-part-of-speech-tagging-text.md)
- [Voyant Tools](episodes/14-textmine-voyant.md)
- [DH-Lab Jupyter Notebooks](episodes/15-textmine-dh-lab.md)
- [DH-Lab apps](episodes/16-textmine-dh-lab-app.md)
- [Practice Review - Simple Exerecices](episodes/review.md)
- [About](episodes/01-textmining-intro.md)

## Program: 

Part I: Getting started  
9-9:15: Introduction: [What is text mining?](https://www.ub.uio.no/english/libraries/dsc/research-methods/text-mining/)
 | [Text mining types](https://www.ub.uio.no/english/libraries/dsc/research-methods/text-mining/text-mining-types.html) | [Text mining tools](https://www.ub.uio.no/english/libraries/dsc/research-methods/text-mining/tools-software-bundles.html)  
9:15-10: Getting started with Python  
[Introduction to Jupyter](episodes/02-jupyter-notebook.md), [Python](episodes/03-python-basics.md), and [NLTK](episodes/04-tokenising-text.md).   
How the Python program works (the math behind it with strings and loops).  
How Python code can be used to text mine.  
  
10-10:15: Break  
  
Part II: Text Mining the Medical History of British India   
10:15-11:  
[Preprocessing dataset](episodes/05-preprocessing-dataset.md)  
[Concordances](episodes/06-concordances.md)

11-11:15: Break

11:15-12:  
[Regular expressions search](episodes/07-regular-expression-search.md)  
[Counting tokens](episodes/08-counting-tokens.md)  
[Frequency distributions and word clouds](episodes/09-frequency-distributions.md) - **plots**  

12-13: Lunch

Part III: Text Mining Inaugural addresses  
13-14:  
[Lexical dispersion](episodes/10-lexical-dispersion-plot.md) (inaugural addresses) - **plots**    
[Plotting frequency over time](episodes/11-plotting-frequency-over-time.md) - **plots**  
[Collocations](episodes/12-collocations.md) (with specified measured)  
[Part-of-Speech tagging](episodes/13-part-of-speech-tagging-text.md) - **plots**  
  
14-14:15: Break  

Part IV: Text Mining with Voyant and DH-Lab   
14:15-14:45: Tour and demonstration of [Voyant](episodes/14-textmine-voyant.md) and [DH-Lab notebooks](episodes/15-textmine-dh-lab.md) and [DH-Lab apps](episodes/16-textmine-dh-lab-app.md)  
  
14:45-15:35: Individual work in Python, Voyant, or DH-Lab  
15:35-15:50: Q&A, group discussion of tools, discuss assignment and assignment schedule  
15:50-16: Course evaluation  

### Suggestions for individual practice:

**Python**: [text mine other corpora made available by NLTK](episodes/review.md), e.g.: 
Project Gutenberg, Chat Corpus, Personals Corpus, Wall Street Journal  
CODE: Concordances, Words in Contexts (similar, common), Collocations, Plots (Dispersion & Frequency Distribution)

**Voyant**: text mine Inaugural Address Corpus (or another corpus from NLTK), comparing functionality provided by Voyant with what you did in Python:  
TOOLS: Cirrus (word cloud based on frequencies), Trends (word dispersions), KWIC (concordances), Topics (topic modelling with term clusters)
(w/[many more tools](https://voyant-tools.org/docs/#!/guide/start) available, incl. graphs and plots for visualizing word frequencies, distributions, proximities, collocates, correlations)

**DH-Lab**: build corpus from the National Library and text mine with the [provided Python code](https://www.nb.no/dh-lab/digital-tekstanalyse/) in Jupyter and/or [applications](https://www.nb.no/dh-lab/apper/)  
TOOLS: Corpus builder, Concordances, Collocations, Frequency Distributions, Topic Modelling, Named Entity Recognition (NER), and Part-of-Speech Tagging (POS)
