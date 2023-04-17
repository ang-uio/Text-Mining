## Text Mining with Voyant Tools

Keypoints:
- Voyant is user friendly and accepts a large variety of formats with little preprocessing.
- Voyant offers a rich range of plots, graphs, and networks to visualize word frequencies, distributions, proximities, and collocates.
- The tool menu is extensive and includes: Cirrus (word cloud based on frequencies), Trends (word dispersions), KWIC (concordances), Topics (topic modelling with term clusters), and Correlations.

[Voyant Tools](https://voyant-tools.org/) is an open-source, web-based application for performing automated computational text analysis on documents. It can be used to analyze online texts you link to and texts you upload, and it accepts a number of different file formats, such as docx, pdf, txt, etc. Voyant is popular among scholars in the digital humanities and has a large, international user base. It does not perform linguistical text analysis such as part-of-speech tagging or named entity recognition, but is highly user friendly, provides nice visualizations, and has a rich functionality. See [the list of tools](https://voyant-tools.org/docs/#!/guide/tools) here.

Acknowledging the limitations of its pre-programmed functionalities, Voyant welcomes users to develop their own tools using Voyant's functionality and code, and endorses the use of other tools, in particular Python with Jupyter Notebook.

Access Voyant Tools at [voyant-tools.org](https://voyant-tools.org/).

Get started:
- Voyant has an extensive [help menu](https://voyant-tools.org/docs/#!/guide/start) for all the functions, and also a [tutorial/workshop](https://voyant-tools.org/docs/#!/guide/tutorial) page. 
- [A Beginner’s Guide to Using Voyant for Digital Theme Analysis](https://hcommons.org/deposits/item/hc:49487/) (2022) by Randa El Khatib and Shawna Ross, published at the Humanities Commons, provides a case-based illustration for how to use Voyant in literary criticism to carry out a digital thematic analysis.

## Topic Modelling 

Topic modelling, sometimes referred to as “theme modelling”, is a method that enables analysis of words’ co-occurrence patterns in texts. Statistical calculations are performed by an algorithm, the output of which allows for grouping, or clustering, of words under the concept of a topic. Despite these clusters being nothing more than words grouped by statistical analysis, a researcher may glean interesting information about the thematic structure of texts through this method.

There are several algorithms used in topic modelling. Latent Dirichlet Allocation (LDA) and BERTopic are two examples. The outputs of these two algorithms are about equivalent, despite being different algorithms.

Voyant Tools features an implementation of LDA, which requires relatively little previous experience with topic modelling to use. You can read more [about Voyant's Topics tool](https://voyant-tools.org/docs/#!/guide/topics) and the algorithm behind it under the help menu. Voyant's topic tool uses an implementation of LDA called jsLDA. Words in each document are randomly assigned to a specified number of topics (you can determine the number of topics). The algorithm then goes through a number of iterations (50) and tries to refine the model of which terms are best suited to which topics (based on co-occurrence in the documents).

Topic modelling may also be done through Python. The LDA algorithm is implementd in the open-source Gensim Python package. The [DH-Lab at the National Library of Norway](https://www.nb.no/dh-lab/) has written [example code](https://nationallibraryofnorway.github.io/digital_tekstanalyse/cookbook/4.1.topic_modelling_with_LDA.html#) in Python to text mine their digitized collection with Gensim-LDA, you can find it in their open collections of Jupyter Notebooks. They have also made a [web-based app](https://dh.nb.no/apps/temaer/) based on their API for topic modelling with LDA.

[Index](https://ang-uio.github.io/Textmining/)
