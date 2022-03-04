
# Design and Implementation of an Information Retrieval System


This repository provides a prototype of an Information Retrieval system designed using Python Jupyter notebook.



#  Introduction


This repository describes a recommended way of implementing a textual search engine on a given corpus or a collection of documents. Our main aim of this assignment was to implement a simple information system that can perform the indexing of the text, perform different queries over the text and provides a set of most relevant documents for the query.

## Roadmap

-The project is entirely done in python programming language.
- The project can be found in the IR_System_KhizerBiyabani.ipynb, it is a python notebook that contains the implemented system.
- At first you need to load the dataset, using a XML parser, in this case you have to use the import xml.etree.ElementTree python library, using the following command.
```bash
  pip install xml
```
- You will need to parse the xml documents in the COLLECTION folder. 
- Please make sure to add the location of your document and query collection of '.xm' files as shown below:
![loadingthe_data](https://user-images.githubusercontent.com/39568831/156712815-20b94730-67f9-4d1e-be7a-6530204e5864.jpg)
- Also, for pre-processing of the text you may download and install nltk (Natural Language Toolkit)
```bash
  pip install nltk
```
NLTK is used for text pre_processing like tokenisation, lemmatization, POS Tagging, Stemming etc.




