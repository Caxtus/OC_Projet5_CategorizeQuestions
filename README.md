# OC_Projet5_CategorizeQuestions
OpenClassroom Projetc - Machine Learning Engineer - Categorize questions with StackOverflow

## I. The datasets
In this project, 3 datasets are used.
The first one - data3 - is the on extracted from the website DataExchange and propose the full data as it's given by the website stackoverflow
The second one - data_synonyms - is also provided by the same website and provides a list of tags proposed by the website stackoverflow. This list of tags is composed of source tags and target tags: it helps building a better cleaniong of the tags list.
The last one - clean_dataframe - is the on built after all the cleanings I work on and allows working on the testing models part.

## II. The cleaning part
The cleaning is done in 3 parts: cleaning of text, cleaning of tags, and visualizations. About the Text, i chose to clean first using BeautifulSoup and nltk fubctions to export the 'text' and build a new column composed of both title and body of the questions. Then a tokenization and some stemming or lemmatization end the cleanding. About the tags, I worked samely to extract here a list of the tags associated to each text part, and compare to the dataset data_synonyms to offer a better cleaning. I chose to work on only 100 tags, which is sufficient here for the models. Then about the visualisations, i let you discover what this code has to offer.

## III. The models part
I work on two part: first with a lemmatized text, and then with a stemmed tex. For both parts, i used unsupervised and supervised models: such as latent dirichlet allocation, nmf for unsupervised parts, and logistic regression, svm and neural networks. You can see i have computed the algo time run, accuracy and weighted average F1 scores, and some visualisations in order to have an idea of what the models actually do, and how to choose the best hyperparameters.

Fell free to contact me should you have any question
