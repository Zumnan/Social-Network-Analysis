# Social-Network-Analysis
Sentiment Analysis for Social media

Opinion mining, also referred to as sentiment analysis, focuses on opinions that separate out good or negative thoughts. Text mining and the NLP model are used in sentiment analysis to extract sentiment (a belief or statement that is held or expressed) from unstructured text data. Sentiment research can be used in industries including social media, customer support, trade, and brand awareness. Sentiment analysis has become the focus of social media research as a result of the development of text mining and natural language processing (NLP) in response to the proliferation of global data throughout time. Sentiment analysis has also experienced a rapid expansion in social media. As social media platforms proliferated, they spawned new features like forum discussions, blogs, reviews, comments, reactions, and postings. These features act as platforms for sentiment analysis and decision-making, and all that is required is the use of the appropriate tools, like the aforementioned NLP, text mining, and machine-learning models like Logistic Regression. In order to extract subjective information from natural languages, sentiment analysis is used. Finally, various techniques will be employed to analyse Twitter data sets. Positive and negative Frequencies (LR Model accuracy 77.92%) and Bag-of-words (LR Model accuracy 88.52%) appear to be less accurate than TF-IDF (LR Model accuracy 88.65%).

The following steps must be considered in order to process data in a rule-based system;
Cleaning text
Tokenization
Part of Speech tagging
Stopwords removal
Obtaining stem words

We utilize the Logistic Regression to estimate our tweet sentiment because it is scalable.
The process of estimating the association between a dependent variable and one or more explanatory factors is known as logistic regression. For instance, your weight is a dependent variable, and the explanatory variable is the ratio of what you eat to gain weight. In logistic regression, a binary dependent variable is modelled using the logistic function.
Logistic Function
α(t)=1/(1 +e^(-t) )

t=β_0+β_(1 ) x_1+⋯+β_n x_n     Linear Combination

where β are learned parameters
Where x are explanatory input variables

Applied Text mining Using Python, and NLP Techniques for Sentiment Analysis for Tweeter Datasets
The Processes involved are listed below and discussed in full in the HTML extracted code from Jupyter Notebook
-	Text Mining 


Text mining and NLP


-	Text Normalization



Features cleaning
Tokenization
Stemming
Lemmatization

-	Text Vectorization



Text Representation
Positive/negative
Bag-of-Words
TF-IDF

-	Sentiment Analysis



Logistic Regression
Model Training
Model Evaluation
Model prediction



NOTE: Look for .csv file named "" this is where our tweet datasets are, without uploading this file on Jupyter Notebook or your code editor you won't be able to visualize
