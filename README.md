# Machine Learning approach to Bengali Parts of Speech Tagging



## About the Project:

This project has been done as the part of Minor Project submission at Heritage Institute of Technology under the Mentorship of Prof. Sandipan Ganguly (HIT-K).

### Introduction to BNLP (Bengali Natural Language Processing) Toolkit:

A library with pre-trained model for POS Tagging including Word Vectors, Name Entity Recognition.

## Installation

* 
  pypi package installer(python 3.6, 3.7, 3.8 tested okay)

  ``pip install bnlp_toolkit``

  or Upgrade

  ``pip install -U bnlp_toolkit``


### Process:


- We have first used Natural Language ToolKit or NLTK library to define & apply basic POS tagging on English Corpus.

- In the next step, we took a small Bengali Corpus & tokenized each Bengali words from sentences individually using BasicTokenizer from BNLP under Rule-Based Approach. Then the same applied on two larger Bengali corpora.

- In next step, we have used NLTKTokenizer from BNLP to tokenize Bengali small corpus into two phases. One is in Word Tokenizing & second one is in Sentence Tokenizing under Rule-based approach. Word Tokenizer tokenized Bengali Words while Sentence Tokenizer tokenized each sentences separately. Then applied the same on two larger Bengali Corpora.

- Next we used SentencePieceTokenizer to apply Unsupervised Learning on two Bengali Corpora.

- In the next step, we used POS function with pre-trained model from BNLP & took a small Bengali Corpus to tag Bengali words & categorize them into different Parts of Speeches under Conditional Random Field based approach.

- In the next we have embedded Bengali Words of a corpus using BengaliWord2Vector with pre-trained model from BNLP to get the vector shape of words & their values under Deep Learning approach.

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

## Read on ResearchGate:

https://www.researchgate.net/publication/359257508_Machine_Learning_approach_to_POS_Tagging_in_Bengali_Language_Project_Report

## References taken from:

1. https://bnlp.readthedocs.io/en/latest/
2. https://github.com/sagorbrur/bnlp
3. https://www.researchgate.net/publication/348957805_BNLP_Natural_language_processing_toolkit_for_Bengali_language
4. https://medium.com/analytics-vidhya/bengali-pos-part-of-speech-tagging-using-indian-corpus-e85f47d3ad65
5. https://nltr.itewb.gov.in/

#### BNLP Developer Credit: Prof. Sagor Sarker (https://github.com/sagorbrur)

