## Sentiment Analysis Project - Public Opinion on news
Anna Errichiello
MSc Data Science and Economics, University of Milan

This contribution develops an analysis over the New York Times Comments dataset, which contains information about comments made on many articles of the New York Times, that have been published in the period from January to May of 2017 and in the period from January to April of 2018. This project aims at defining which of the topics to which articles belong are most controversial. To state whether a topic is controversial, we need to consider two main factors: how much people talk about it and whether there are conflicting opinions. To study the controversy of a field of discussion, it is important to start form the comments to the articles pertaining to that topic and that is also the reason why it is important to study which are the factors that trigger a response or a reaction and the user interactions. This is what the article 'What creates interactivity in online news discussions? An exploratory analysis of discussion factors in user comments on news items' published by the Journal of Communication talks about. This project is aligned with the idea that there are many discussion factors that generate user interactions. Furthermore, responding to a user comment is the first step to initiate an interpersonal discussion. In the literature there are many studies that suggest which factors may be consider in understanding whether a comment can be considered as an 'interactions-generator' or not. One of the proposed studies aims to determine whether a user comment receives response comments (i.e., feedback) from other users on the basis of factors revealed from previous studies. The feedback variable has been then used in order to compute a binary logistic regression, that allows to find which are the comments that will eventually generate responses from other users. These considerations are the basis for this contribution.

The repository is organized in three files:
.	Articles.ipynb: it contains the importation of the data from Kaggle and the part related to the Topic Model
.	Comments.ipynb: it contains the part related to the definition of the 'successful' comments
.	ControversialTopics.ipynb: it reports the last part of the project related to the research of the most controversial topics.
The project is also accessible through the following link that brings to the Colab version of the notebook: https://colab.research.google.com/drive/1Aly77BHpQmSorO6h7gcGSA7qJY28OBlA?usp=sharing



