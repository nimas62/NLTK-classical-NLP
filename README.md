# classicalNLP
Explore the commonly used NLTK packages for classical NLP tasks.


NLTK-Text-Corpora.ipynb Covers:

1- Loading the nltk.corpus corpora.

2- Using corpus.raw corpus.words corpus.sentence for tokenizing and counting.

3- Using the corpus as string, or tokens list.

4- Tokenizing a raw string using split()

   Note: Doesn't work well. e.g. can't extract the ponctuations like "I asked her: how are you?"  >>> gives ...[her:],...,[you?]
	
5- Tokenizing a raw string using nltk work_tokenize. Gives good results. Can tokenize ponctuations.

6- Creating a text object using Text method from nltk.text package

7- Exploring text for concordance, similarity and common_contexts


More info at http://www.nltk.org/py-modindex.html

Installing NLTK:

http://www.nltk.org/install.html
