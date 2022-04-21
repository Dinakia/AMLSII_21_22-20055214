# AMLSII_21_22-20055214

This task is the two-category problem of emotional analysis of IMDB film reviews. The purpose of this document is to inform the task content, the organization form of the document, the necessary packages and the running problems of the code.

1.Classification of documents:
Folder main code contains all deep learning models, while folder contract code contains random forest algorithm files reproduced from kaggle competition. main.py is the main program that runs the program.

2.Calls to external libraries:
python                  3.8.12
tensorflow              2.6.2
numpy                   1.19.5
matplotlib              3.3.4
pandas                  1.1.5
nltk                    3.6.7
beautifulsoup4          4.11.0
sklearn                 0.0
gensim                  4.1.2
wordcloud               1.8.1
keras                   2.6.0
seaborn                 0.11.2

3.dataset:
Use these three files in the data folder：
labeledTrainData.tsv
testData.tsv
imdb_master.csv

4.For main code folder:
The code file of BILSTM model is located at A/BILSTM.ipynb 
The code file of GRU model is located at A/GRU.ipynb 
The code file of LSTM model is located at A/LSTM.ipynb 

5.For contract code folder:
The code file of random forest model is located at contract code/randomforest.ipynb 
