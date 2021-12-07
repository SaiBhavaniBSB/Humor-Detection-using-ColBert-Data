# Humor-Detection-using-ColBert-Data
#Introduction

Humor is a exceptionally complex character-istic concept which characterizes human be-ings and social substances.  Humor is an fun-damental component in individual communica-tion.  Because of its subjective nature,findingthe structures behind humor, recognize humorand extraction of humor remains a challenge.Humor includes data related to linguistic, psy-chological, neurological and sociological com-ponents. For instance, cognitive aspects as wellas social information are some of the factorsthat should be analyzed in order to understandhumor properties.

#Data

The dataset employed for the detection of Humor isthe ”ColBERT Dataset” which consists of 200k la-beled short texts distinguished between humor andnon-humor. News dataset includes 200,853 newsheadlines. Headlines are extracted from categoriesincluding politics, wellness, entertainment and par-enting. Jokes dataset contains 231,657 jokes/humorshort texts taken from Reddit communities.
Train Dataset :
![image](https://user-images.githubusercontent.com/95667642/144960423-9d9ff877-fab9-4fd6-85eb-f2ce18ca8b3c.png)
Test Dataset :
![image](https://user-images.githubusercontent.com/95667642/144960440-cd07ccd9-4ac7-41a9-887a-7d6ecc90e1f1.png)

BERT Model :

BERT is acronym for Bidirectional Encoder Rep-resentations from transformers. BERT is a modelthat is used to represent text.  For a given inputstatement to have a deeper sense of context, BERTemploys bidirectional training and vector represen-tations are created for each word as the output.

Naive Bayes:Naive Bayes Classifier is simple and effectiveclassification algorithm which helps in building fastmachine learning models with quick predictions

#Evaluation Parameters

Precision : The ability of a classification model toidentify the relevant data points.Precision is num-ber of true positives divided by the number of truepositives plus the number of false positives.
Recall: Ability of a model to find all the relevantcases within a data set.  Recall is defined as thenumber of true positives divided by the number oftrue positives plus the number of false negatives.
F1  score  :  F1  Score  is  the  weighted  averageof Precision and Recall.  
F1 Score = 2*(Recall *Precision) / (Recall + Precision)
Accuracy:  Accuracy is the performance mea-sure and it is simply a ratio of correctly predictedobservation to the total number of observations



We are using Colbert Data which are uploaded in the project as Humor_Train_Data.csv and Humor_CorrectEstimation_Data.csv
The project is done in Google Collabaration, below are the steps to execute the code in Google Colab.
Downlaod the Team2_Humor_Detection.ipynb file along with two data files.
Upload the train and test files into your drive.
Open Google collaberator(https://research.google.com/colaboratory/) in chrome and click on upload button on the screen. Else navigate to "File" and click on "Upload Notebook".
Select the downloded Team2_Humor_Detection.ipynb file.
Navigate to Runtime and click on "Change Runtime Type" to "GPU".

#Conclusion
There is a lot of demand for automatic humor detecting systems in the market as it can be used in chat-bots and AI.We still consider that detecting someone’s sense of humor is a difficult problem. As with humor, all these figures of speech depends on the listener or reader to be in on this context.  The results are highly dependent on the datasets utilized and thus high quality of the datasets will lead to more precise results.
