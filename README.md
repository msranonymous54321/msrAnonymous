# msrAnonymous
This is a GitHub repository for submission to the  https://2025.msrconf.org/.  
The paper title is: Automated Duplicate Bug Report Detection in Large Open-Source Projects
This project is structured in terms of different versions. Each version begins with a cell of all the libraries you need to import for that version to run.
All versions can be run independently. 
The zip file of bug reports can be download here: XXXX
Here are the versions described below:

Deep_learning_and_Native_Bayes.ipynb -tested MLP, BERT, and Naive Bayes for determining if a bug is a duplicate or not (binary classification) 

GPT_Summarization.ipynb-  Used API to summarize bug reports and then used cosine similarity to determine if they were duplicates 

Testing_different_Threshold_Values.ipynb- Tested different threshold values for cosine similarity to classify reports as duplicate or not duplicate

Time_sorted_by_clutser.ipynb-  Separated the data frame into different time frames rather than topics and compared cosine similarities of bug reports

Top_k.ipynb- Created a function to output k number of similar bugs rather than bugs above a certain similarity threshold

Topic_modeling.ipynb- Splits bug reports into topics using LDA topic modeling and compares bugs in the same topic using cosine similarity 
