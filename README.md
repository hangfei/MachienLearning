MachienLearning
===============
##Description
Predicted the rating of Yelp reviews given review text and other review information
- Processed the raw data, including information retrieval, feature selection, data rescaling, bigrams
- Implemented and combined various models, including PCA/SVD, SVM, Logistic Regression
- Visualized sentiment analysis results
- Enabled restaurants to improve their services via the feedback of low rating review

##Project Architectrue
We have tried multiple methods to pushing the edges of our results. The optimal one(with best accuracy and best speed) is in the init_model.m and make_final_prediction.m file(You could try to run script_test.m to test).
For other models we have develop, please check the README file.
Data
The data is in the data package, including raw data and some other processed data.

####Results:
RMSE: 0.89
(Off by at most half a star of the actual result for a review.)


####Supporting Package:
- Libnear(http://www.csie.ntu.edu.tw/~cjlin/liblinear/)

##Installation instructions 
Matlab, and related packages


##Where to get help
TBD



##Contribution guidelines
TBD

##Contributor list
Hangfei Lin, Di Mu, Sanjay Paul

##Credits, Inspiration, Alternatives



- - - -
####Infographics for key words of high rating and low rating.
Credit: Di Mu
![picture alt](https://raw.githubusercontent.com/hangfei/MachienLearning/master/Infograph_good.jpg "Title is optional")

![picture alt](https://raw.githubusercontent.com/hangfei/MachienLearning/master/Infograph_bad.jpg "Title is optional")
