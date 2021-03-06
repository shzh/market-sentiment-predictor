market-sentiment-predictor
===========

@authors: Joshua Lang, Robert Meyer, Shuo Zheng
Implemented in Python

The project attempts to utilize machine learning and language processing 
concepts to determine a correlation between market data and public sentiment 
as expressed through the New York Times financial news.

We've included a dataset from 2010-2014 of intraday market movements of 
the Dow Jones Industrial Average (DJIA) gathered using the Yahoo Finance
API.

svm.py - the support vector machine implementation of our predictor. You
can run it by invoking:

python svm.py

or

python2 svm.py

depending on the version of Python that your operating system defaults to.

To play the interactive game with the SVM giving decision recommendations,
run:

python svm_interactive.py

or

python2 svm_interactive.py
