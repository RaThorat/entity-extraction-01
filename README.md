# entity-extraction-01
Entity Extraction from PDF files using spacy NLP model

The extraction of information such as persons name, organisation, adresses, events, year, keywords are necessary for anonimty check of the text, to classify or cluster text etc.

#assigning the NLP model

#https://spacy.io/usage/models

#you need to download the spacy model before starting this step. 

#More info on the website of spacy to download spacy model. 

#You can also load your own custom made model if you want

#creation of a dataframe to include the columns 

#input files path where your pdf files are

#reading the path

#looping over the pdf files

#if the filename is clear and distinct

#Extracting the basename of the file

#Extract the filename from the basename of the file
    
#if the filename is not the official name  of the application

#filename="DMP_"+str(i)
    
#using pdfplumber for processing the pdf files
   
#Load SpaCy Model

#initialize entities and labels variables

#collecting the entities and the corresponding labels of the file in the loop in a dataframe

#assigning all the datatypes within df as string

#dropping the duplicates

#appending data of the file in the loop 
