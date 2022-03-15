# Machine Learning approach to Bengali Parts of Speech Tagging

## Bengali Corpus Parts of Speech Tagging using BNLP (Bengali Natural Language Processing) toolkit- 
A library with pre-trained model for POS Tagging including Word Vectors, Name Entity Recognition.

-----------------------------------------------------------------------------------------------------------------------------------------------------------


We have first used Natural Language ToolKit or NLTK library to define & apply POS tagging on English Corpus.

In the next step, we have differentiated Bengali small corpus into individually Tokenized Bengali words using BasicTokenizer from Bengali Natural Language Processing Toolkit Library or BNLP under Rule-Based Approach. Then the same applied on two larger bengali corpora.

In next step, we have used NLTKTokenizer from BNLP to tokenize Bengali small corpus into two phases. One is in Word Tokenizing & second one is in Sentence Tokenizing under Rule-based approach. Then applied the same on two larger Bengali Corpora.

Also we used SentencePieceTokenizer to apply Unsupervised Learning on Bengali Corpora.

In the next step, we have called POS function & pre-trained model from BNLP to tag words into different Parts of Speeches. We took Bengali small corpus & applied POS tagging to categorize words into their corresponding Parts of Speeches under Conditional Random Field based approach. Then applied on two larger Bengali Corpora.

We found false positive result as well & calculated Confusion Matrices to get Precision, Recall & F1 value.

We have used dataset from NLTR & got 90% accuracy.

In the next we have vectorized Bengali Words using BengaliWord2Vector function using pre-trained model from BNLP to get the vector shape of words & values under Deep Learning approach. 


Tools:

1. Jupyter Notebook/Google Cloab
2. BNLP Library. Reference taken from: Prof. Sagor Sarker (Bangladesh) on GitHub.
3. Research papers on Bengali Pos Tagging.


Mentor: Prof. Sandipan Ganguly (HIT-K).

Developers:

1. Rajdeep Das
2. Arghyadeep Banerjee
3. Soham Chakraborty
4. Tanmay Guchhait
5. Debabrata Maity
6. Alik Sarkar
7. Sanju Manna


For reference:

https://github.com/sagorbrur/bnlp

 Reference source: Sagor Sarker
