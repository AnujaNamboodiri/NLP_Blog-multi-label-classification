# NLP_Blog-multi-label-classification

DOMAIN: Digital content management
• CONTEXT: Classification is probably the most popular task that you would deal with in real life. Text in the form of blogs, posts, articles, etc.
are written every second. It is a challenge to predict the information about the writer without knowing about him/her. We are going to create a
classifier that predicts multiple features of the author of a given text. We have designed it as a Multi label classification problem.

• DATA DESCRIPTION: Over 600,000 posts from more than 19 thousand bloggers The Blog Authorship Corpus consists of the collected posts of
19,320 bloggers gathered from blogger.com in August 2004. The corpus incorporates a total of 681,288 posts and over 140 million words - or
approximately 35 posts and 7250 words per person. Each blog is presented as a separate file, the name of which indicates a blogger id# and
the blogger’s self-provided gender, age, industry, and astrological sign. (All are labelled for gender and age but for many, industry and/or sign is
marked as unknown.) All bloggers included in the corpus fall into one of three age groups:
• 8240 "10s" blogs (ages 13-17),
• 8086 "20s" blogs(ages 23-27) and
• 2994 "30s" blogs (ages 33-47)
• For each age group, there is an equal number of male and female bloggers. Each blog in the corpus includes at least 200 occurrences of
common English words. All formatting has been stripped with two exceptions. Individual posts within a single blogger are separated by the
date of the following post and links within a post are denoted by the label url link.

• PROJECT OBJECTIVE: To build a NLP classifier which can use input text parameters to determine the label/s of the blog. Specific to this case
study, you can consider the text of the blog: ‘text’ feature as independent variable and ‘topic’ as dependent variable

Steps and tasks: 
1. Read and Analyse Dataset. 
A. Clearly write outcome of data analysis(Minimum 2 points) 
B. Clean the Structured Data 
i. Missing value analysis and imputation. 
ii. Eliminate Non-English textual data. 
Hint: Refer ‘langdetect’ library to detect language of the input text)

Preprocess unstructured data to make it consumable for model training. 
A. Eliminate All special Characters and Numbers 
B. Lowercase all textual data 
C. Remove all Stopwords 
D. Remove all extra white spaces

3. Build a base Classification model
A. Create dependent and independent variables 
Hint: Treat ‘topic’ as a Target variable.
B. Split data into train and test. 
C. Vectorize data using any one vectorizer. 
D. Build a base model for Supervised Learning - Classification.
E. Clearly print Performance Metrics. 
Hint: Accuracy, Precision, Recall, ROC-AUC

. Improve Performance of model. 
A. Experiment with other vectorisers.
B. Build classifier Models using other algorithms than base model.
C. Tune Parameters/Hyperparameters of the model/s
D. Clearly print Performance Metrics.

. Share insights on relative performance comparison
A. Which vectorizer performed better? Probable reason?.
B. Which model outperformed? Probable reason? 
C. Which parameter/hyperparameter significantly helped
to improve performance?Probable reason?. 
D. According to you, which performance metric should be
given most importance, why?. 
