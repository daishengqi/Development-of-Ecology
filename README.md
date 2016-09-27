# The History of Ecology based on Massive Datasets 
This is the Git for paper "From 1915 to 2015, the evolution of ecological research" which proposed a new view on the history of Ecology using NLP-based bibliometric methods based on a total of more than 420000 research papers. In this repository you will find: 1) Source codez for data analysis and visualziation, 2) Detailed reference information and 3) Original data download.

## Datasets
* **Bibliometric Data**: A total of 423585 research papers were collected in this study. This dataset was collected using formula: `WC = Ecoogy AND PY = (1915-2015) AND LA = English` in the form of utf-8 full record at Thomson Reuters Web of Science. Data of year 2016 were also downloaded but not used in this research.

## Algorithms
* **ISI Data Reconstruction**: Original ISI (Bibliometric) Data contained too much data which is not necessary for our analysis, to make data simple and save places for storage, useful attributes in ISI table were transform into an array and imported into MySQL. Avaliable atrributes includes AU, AF, TI, SO, AB, C1, RP, EM, DI, as PT and ER are also used for tagging. 

## Data Visualization

## Contact
I'm still working on this project, if you've discovered a bug or something else you want to change, feel free to contact me at: daishengqi@hotmail.com
