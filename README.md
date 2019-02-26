
#  Scientific Journal Reccomendation:

## Installation: 
1. Download NLTK word corpus
2. Install wordcloud
3. Install tensorflow 

## Prerequistes:
1. Datasets:
link - https://archive.ics.uci.edu/ml/datasets/NIPS+Conference+Papers+1987-2015
2. Tensorflow installation in anaconda:
conda install -c conda-forge tensorflow
3. Wordcloud installation:
conda install -c conda-forge wordcloud 
4. nltk download:
conda install -c anaconda nltk 

##  Description:
This a unsupervised reccomendation system of the Scientific Journals. Firstly we have imported the libraries and dataset processed the raw text and saved the process dataset into a new csv file.All this operation is done in journal_reccomendataion_1.ipynb

On the second file, operations like removing missing values takes place.Then we do Exploratory data analysis of the data set like word cloud clustering and 2D t-SNE and also used pyLDAvis to visualize the cluster and most occuring word and to predict the suitable number of cluster.

We have used  Count vectorizer to create a word vector which is fed into Latent Dirichlet Allocation,which gives us likelihood of the document to occur in the given topic cluster.Then we try to find the root mean square error to predict between the given document with all other document as a result we get the R.M.S Error for every comparation. We sort the given error in ascending order and reccomend 10 least errorneous title as a reference for the research paper along with error value.

## Example:
!['Result']('/images/crop.png')
