# CSE508_Winter2024_A1_MT23053
Notebook of Kaggle has been used to run the .ipynb files
file directory for the same has been mentioned
data provided in the sheet was downloaded and uploaded to kaggle 

**#Question 1**
Searching the directory with files having .txt extension we read each file and then call preprocess function which first makes them lowercase then tokenize them and and uses modules in nltk library to remove stopwords and punctuation

**#Question 2**

Using the tokenised output we first create the unigram index and then use the pickle module to store the index to our directory

We are first preprocessing the available text in the file directory

After that separate function for each given operation is created

User is providing the query and the operations needed to be performed (separated by a comma)

As per the query we are inserting the results in an empty list and returning the list results as the output for the query

**#Question 3**

We use the tokenised output and do processing on the data and then save the positional index

Function preproces_text if for preprocessing where we remove stopwords, punctuations and blank space tokens

Function create_positional_index is for creating positional index where we are traversing the file directory and then accessing the preprocessed text

if the token is not in positional_index then we are creating an entry for the same and if token is present but the file in which it has occurred is not available in the index we are appending the position to the index

Afterwards we are using pickle to save the positional _index


