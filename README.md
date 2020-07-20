# Twitter_Sentimental_Analysis

OFFENSIVE LANGUAGE IS PERVASIVE IN SOCIAL MEDIA. INDIVIDUALS FREQUENTLY TAKE ADVANTAGE OF THE PERCEIVED ANONYMITY OF COMPUTER-MEDIATED COMMUNICATION, USING IT TO ENGAGE IN BEHAVIOUR THAT MANY OF THEM WOULD NOT CONSIDER IN REAL LIFE.ONLINE COMMUNITIES, SOCIAL MEDIA PLATFORMS, AND TECHNOLOGY COMPANIES HAVE BEEN INVESTING HEAVILY ON WAYS TO COPE WITH OFFENSIVE LANGUAGE TO PREVENT ABUSIVE BEHAVIOUR IN SOCIAL MEDIA.ONE OF THE MOST EFFECTIVE STRATEGIES FOR TACKLING THIS PROBLEM IS TO USE COMPUTATIONAL METHODS TO IDENTIFY OFFENSE, AGGRESSION, AND HATE SPEECH IN USER-GENERATED CONTENT (FOR EXAMPLE, POSTS, COMMENTS, MICROBLOGS, ETC.)


ABSTRACT
Toxic online content has become a major issue in today’s world due to an exponential increase in the use of internet by people of different cultures and educational background. Differentiating hate speech and offensive language is a key challenge in automatic detection of toxic text content.


PROBLEM STATEMENT
In this project,approach is proposed to classify tweets on Twitter into offensive tweet or not using various classification algorithms and checking their accuracy.


BASIC TECHNOLOGY BEHIND THIS PROJECT
Natural language processing (nlp)
It is an area of computer science and artificial intellligence that is concerned with the interaction between computers and humans in natural language. its goal is to enable computers to understand language as well as we do. according to estimates, about 79% of all available data is in the textual form, which is highly unstructured in nature. one of the obstacles to the achievement of proper nlp is that human language is complex and can be abstract. one word can be used to express various different meanings.


WORKFLOW
• Imported the necessary libraries.
• Reading the dataset - the data is retrieved from csv file.
• Cleaning the dataset - for each line in the dataset, unnecessary words which are not useful in our classification are removed. apart from this, symbols or emticons are removed. all words are converted into lowercase letters so that there remains no discrepancy between uppercase and lowercase words.
• lemmatization is an organized and step-by-step procedure of obtaining the root form of the word, using vocabulary and morphological analysis.
• vectorization is a methodology in NLP to map words or phrases from vocabulary to a corresponding vector of real numbers which used to find word predictions, word similarities/semantics.
• Model making and evaluation by calculating the accuracy.

MODELS AND THEIR ACCURACY
Logistic Regression - 0.9581812493482115
Naive Bayes - 0.9471269162582125
Decision Tree - 0.9442069037438732
Random Forest - 0.9615184065074565
