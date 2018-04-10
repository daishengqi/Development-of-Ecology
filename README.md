# The Development of Ecology based on Massive Datasets 
This is the Git for paper "Trends and biases in ecological concepts during the last century" which is under the project of a bibliometric exploration of more than 420,000 articles from 1915-2015. 
In this project, we proposed a new view on the development of Ecology using Nautral Language Processing (NLP) based bibliometric methods based on a total of 423585 research papers. Further in this repository you will find: 1) the jupyter notebook (resource codes with annotation) for data preprocessing, analysis and visualziation, 2) Detailed information on methods and references and 3) Download links for the raw data, processed data and visualizations.

## Bibliometric Datasets
* **Bibliometric Data**: A total of 423585 research papers were collected in this study. This dataset was collected using formula: `WC = Ecoogy AND PY = (1915-2015) AND LA = English` in the form of utf-8 full record at Web of Science in Apr. 2017, whereas the bibliometric data of year 2016 was also downloaded but not included in the analysis of paper research.

## Algorithms & Packages
* **WoS Data Reconstruction**: Original Web of Science (Bibliometric) Data contained too much fields which was not necessary for our analysis, to make data neat and save places for storage, useful attributes in data table were then transform into an array and imported into MySQL and Python.Pandas.DataFrame. Important atrributes includes AU, AF, TI, SO, AB, C1, RP, EM, DI, ID, DE, as PT and ER are also used for tagging. 

* **NLTK Package**: In this research, functions in NLTK package were frequently used, including tokenization, stemming, stopwords deletion, lemmitazation and POS tagging etc. For detailed information on NLTK package, please visit: https://github.com/nltk/nltk.

* **Word2Vec Algorithm**: Efficient multicore implementations of popular algorithms, such as online Latent Semantic Analysis (LSA/LSI/SVD), Latent Dirichlet Allocation (LDA), Random Projections (RP), Hierarchical Dirichlet Process (HDP) or word2vec deep learning were supported by Gensim, whichi is a Python library for topic modelling, document indexing and similarity retrieval with large corpora. Target audience is the natural language processing (NLP) and information retrieval (IR) community. For more information, please visit: https://radimrehurek.com/gensim/index.html

## Data Visualization
In the paper, we managed to build 4 visualizations to characterize the development of ecological concepts during the last century, which involved:
* **Figure 1:** Basic bibliometric information on ecological articles during 1915-2015.
* **Figure 2:** Temporal trends of ecological concepts and categories.
* **Figure 3:** The preferences of top 30 publishing countries on top 30 ecological concepts quantified by Preference Index
* **Figure 4:** Ecological concept and category ranking relationships between bibliometric statistical analysis and questionnaire survey results on ESA ecologists.

We proposed the major visualization using Python and Microsoft Excel, and we would like to give special thanks to Sci2 tools(https://sci2.cns.iu.edu/user/index.php) and Seaborn(https://seaborn.pydata.org/) for their awesome usability.

## References
Special thanks to William A. Reiners et al. for building ecological concept toolbox, which is greatly instructive in our project. For more information, please reference : 
Conceptual toolboxes for twenty‐first‐century ecologists, WA Reiners, GS Pappas, JA Lockwood, DS Reiners, SD Prager, Ecosphere 9 (2) at https://esajournals.onlinelibrary.wiley.com/doi/abs/10.1002/ecs2.2104
and
100 years of ecology: what are our concepts and are they useful?, WA Reiners, JA Lockwood, DS Reiners, SD Prager, Ecological Monographs 87 (2), 260-277 at https://esajournals.onlinelibrary.wiley.com/doi/full/10.1002/ecm.1243

## Contact
I'm still working on this project, if you've discovered a bug or something else you want to change, feel free to contact me at: daishengqi@hotmail.com or 13110700026@fudan.edu.cn
