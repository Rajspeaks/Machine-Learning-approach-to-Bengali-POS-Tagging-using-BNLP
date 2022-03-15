# Machine Learning approach to Bengali Parts of Speech Tagging

.. image:: https://travis-ci.org/sagorbrur/bnlp.svg?branch=master
   :target: https://travis-ci.org/sagorbrur/bnlp
   :alt: Build Status


.. image:: https://img.shields.io/pypi/v/bnlp_toolkit
   :target: https://pypi.org/project/bnlp-toolkit/
   :alt: PyPI version


.. image:: https://img.shields.io/github/v/release/sagorbrur/bnlp
   :target: https://github.com/sagorbrur/bnlp/releases/tag/1.1.0
   :alt: release version


.. image:: https://img.shields.io/badge/python-3.6%7C3.7%7C3.8-brightgreen
   :target: https://pypi.org/project/bnlp-toolkit/
   :alt: Support Python Version
   

## About the Project:

This project has been done as the part of Minor Project submission at Heritage Institute of Technology under the Mentorship of Prof. Sandipan Ganguly (HIT-K).

### Introduction to BNLP (Bengali Natural Language Processing) Toolkit:

A library with pre-trained model for POS Tagging including Word Vectors, Name Entity Recognition.

Installation
============


* 
  pypi package installer(python 3.6, 3.7, 3.8 tested okay)

  ``pip install bnlp_toolkit``

  or Upgrade

  ``pip install -U bnlp_toolkit``


### Process:

- We have first used Natural Language ToolKit or NLTK library to define & apply POS tagging on English Corpus.

- In the next step, we have differentiated Bengali small corpus into individually Tokenized Bengali words using BasicTokenizer from Bengali Natural Language Processing Toolkit Library or BNLP under Rule-Based Approach. Then the same applied on two larger bengali corpora.

- In next step, we have used NLTKTokenizer from BNLP to tokenize Bengali small corpus into two phases. One is in Word Tokenizing & second one is in Sentence Tokenizing under Rule-based approach. Then applied the same on two larger Bengali Corpora.

- In the next step we have used SentencePieceTokenizer to apply Unsupervised Learning on Bengali Corpora.
- In the next tep we have used Bengali Word2Vec Model to embed Bengali words into their vector shapes.

- In the next step, we have called POS function & pre-trained model from BNLP to tag words into different Parts of Speeches. We took Bengali small corpus & applied POS tagging to categorize words into their corresponding Parts of Speeches under Conditional Random Field based approach. Then applied on two larger Bengali Corpora.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------



![pie-chart](https://user-images.githubusercontent.com/44817007/158359964-970e0bfd-f4f2-4403-8863-a1b9bc1d6e25.png)

![pie-chart-Evaluated result of BNLP](https://user-images.githubusercontent.com/44817007/158361562-969f423a-b890-4bb9-aad4-360b5837c35b.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Confusion Matrix

We found false positive result as well & calculated Confusion Matrices to get Precision, Recall & F1 value.

#### We have used dataset from NLTR & got 90% accuracy.

## Tools:

1. Jupyter Notebook/Google Colab
2. BNLP Library taken from: [Prof. Sagor Sarker](https://github.com/sagorbrur) (Bangladesh) on GitHub.
3. Research papers on Bengali Pos Tagging.


## Mentor: Prof. Sandipan Ganguly (HIT-K).

## Developers:

1. Rajdeep Das
2. Arghyadeep Banerjee
3. Soham Chakraborty
4. Tanmay Guchhait
5. Debabrata Maity
6. Alik Sarkar
7. Sanju Manna


## References takenm from:

1. https://bnlp.readthedocs.io/en/latest/
2. https://github.com/sagorbrur/bnlp
3. https://www.researchgate.net/publication/348957805_BNLP_Natural_language_processing_toolkit_for_Bengali_language
4. https://medium.com/analytics-vidhya/bengali-pos-part-of-speech-tagging-using-indian-corpus-e85f47d3ad65
5. https://nltr.itewb.gov.in/

#### BNLP Developer Credit: Prof. Sagor Sarker (https://github.com/sagorbrur)

