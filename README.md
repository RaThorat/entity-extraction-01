# entity-extraction-01
Entity Extraction from PDF files using spacy NLP model

The extraction of information such as persons name, organisation, adresses, events, year, keywords are necessary for anonimty check of the text, to classify or cluster text etc.

# NLP model

This project uses SpaCy for natural language processing.

# Requirements

You need to download the SpaCy model before starting this project. More information can be found on the SpaCy website.

You will also need pdfplumber to process PDF files.

# Setup

Install the required libraries:

Download the SpaCy model:

    Replace <model name> with the name of the desired model (e.g. en_core_web_sm).

Set the input file path:
    
# Usage

Run the script
    
The script will loop through all PDF files in the input_path directory, extract the entities and labels using the SpaCy model, and store the results in a dataframe.
    
The dataframe will include the following columns:

    'filename': the name of the PDF file

    'entity': the entity identified in the text

    'label': the label assigned to the entity by the SpaCy model
    
Duplicate rows will be removed from the dataframe.

The resulting dataframe can be accessed as a Pandas DataFrame object named 'df'. All data in the dataframe will be stored as strings.
