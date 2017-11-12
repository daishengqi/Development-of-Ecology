# The History of Ecology based on Massive Datasets 
This is the Git for paper "Trends and biases in ecological concepts during the last century: A bibliometric exploration of 420,000 articles from 1915-2015" which proposed a new view on the history of Ecology using NLP-based bibliometric methods based on a total of 423585 research papers. In this repository you will find: 1) the jupyter notebook for data preprocessing, analysis and visualziation, 2) Detailed reference information and 3) Original data downloading links.

## Bibliometric Datasets
* **Bibliometric Data**: A total of 423585 research papers were collected in this study. This dataset was collected using formula: `WC = Ecoogy AND PY = (1915-2015) AND LA = English` in the form of utf-8 full record at Web of Science at Apr. 2016. The bibliometric data of year 2016 were also downloaded but not included in the analysis of this research.

## Algorithms & Packages
* **ISI Data Reconstruction**: Original ISI (Bibliometric) Data contained too much data which is not necessary for our analysis, to make data simple and save places for storage, useful attributes in ISI table were transform into an array and imported into MySQL. Important atrributes includes AU, AF, TI, SO, AB, C1, RP, EM, DI, ID, DE, as PT and ER are also used for tagging. 

* **NLTK Package**: In this research, functions in NLTK package were frequently used, including tokenization, stemming, stopwords deletion, lemmitazation and POS tagging etc. For detailed information on NLTK package, please visit: https://github.com/nltk/nltk.

* **Word2Vec Algorithm**: 

## Data Visualization

## References

## Contact
I'm still working on this project, if you've discovered a bug or something else you want to change, feel free to contact me at: daishengqi@hotmail.com
