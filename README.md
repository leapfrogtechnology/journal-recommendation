#  Scientific Journal Reccomendation 

## Installation 
1.Download NLTK word corpus
2.Install wordcloud
3.Install tensorflow 

##  Description
This a unsupervised reccomendation system of the Scientific Journals.Firstly
we have imported the libraries and dataset processed the raw text and saved 
the process dataset into a new csv file.All this operation is done in journal_reccomendataion_1.ipynb .

On the second file, operations like removing missing values takes place.Then
we do Exploratory data analysis of the data set like word cloud clustering 
and 2D t-SNE and also used pyLDAvis to visualize the cluster and most occuring
word and to predict the suitable number of cluster.

We have used  Count vectorizer to create a word vector which is fed into Latent
Dirichlet Allocation,which gives us likelihood of the document to occur in 
the given topic cluster.Then we 
