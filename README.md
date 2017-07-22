# deezer_report

## Data Science Game 2017 | Online Qualification Phase: Music recommendation

* Started: 12:22 am, Friday 14 April 2017 UTC 
* Ended: 11:59 pm, Wednesday 31 May 2017 UTC (47 total days) 

Deezer is a music streaming app, also available on the web. It proposes more than 43 million tracks and is available in more than 180 countries, through a free limited service and a premium offer. 

This was international student competition where more than 220 universities and around 800 students participated in online qualification round which lasted for 47 days. This competition was hosted on Kaggle. We participated in this competition as a team of 4 students from our university - Berlin School of Economics & Law. https://www.kaggle.com/teamten

## Main files:

* [Final Report](https://github.com/vhwr/deezer_report/blob/master/Final_Report.Rmd) 
* [Feature Engineering](https://github.com/vhwr/deezer_report/blob/master/Final_Report.Rmd)(section 1 to 3 in Final Report)
* [Models- folder](https://github.com/pranavpandya84/deezer_report/tree/master/Models) 
  * [XGBoost Sparse model](https://github.com/vhwr/deezer_report/blob/master/Final_Report.Rmd)(section 4a in Final Report)
  * [XGBoost Numeric model](https://github.com/pranavpandya84/deezer_report/blob/master/Models/XGBoost_Numeric.rmd)
  * [LightGBM](https://github.com/pranavpandya84/deezer_report/blob/master/Models/LightGBM.rmd)
  * [H2O Automated Machine Learning](https://github.com/pranavpandya84/deezer_report/blob/master/Models/H2O_autoML.rmd)
  * [H2O Distsributed Random Forest- Flow](https://github.com/pranavpandya84/deezer_report/blob/master/Models/H2O%20Flow/H2O%20DRF%2023rd%20May/screenshots.rmd)
  * [H2O Deep Learning - Flow](https://github.com/pranavpandya84/deezer_report/blob/master/Models/H2O%20Flow/H2O%20DL%20Flow/Screenshots.rmd) 
* [Data used for other models](https://www.dropbox.com/sh/1ubsg7qhovifgoj/AAAZb1hOTBESDrI3jbuYQkULa?dl=0)
(Data has also been put in zeno server under "60_data_other_models" and steps from above scripts/ models can be replicated. Dropbox link is to download data and try models locally without need of server.)
* [Leaderboard Score Analysis](https://github.com/pranavpandya84/deezer_report/blob/master/Models/LB_Score/report_slides.rmd) 
* [Reference material](https://github.com/pranavpandya84/deezer_report/blob/master/Tuning%20parameters%20-reference%20material/reference.rmd) (Parameters tuning and categorical encoding guide)
* [Official documentation](https://github.com/pranavpandya84/deezer_report/tree/master/Tuning%20parameters%20-reference%20material/docs) (Guide for XGBoost, LightGBM and H2O)


## Statistics about this competition:
![alt text](https://github.com/pranavpandya84/deezer_report/blob/master/Models/LB_Score/deezer_poster1.png)

The goal of this challenge was to predict whether the users of the test dataset listened to the first track of Deezer's own music recommendation algorithm proposed them or not. The evaluation metric for this competition was the ROC AUC.

## Results:

* Model comparison
![alt text](https://github.com/pranavpandya84/deezer_report/blob/master/Models/LB_Score/2.PNG)

* Rank in Germany by Private Leaderboard Score
![alt text](https://github.com/pranavpandya84/deezer_report/blob/master/Models/LB_Score/rank.PNG)

### Top 20 teams/ Finalists
![alt text](https://github.com/pranavpandya84/deezer_report/blob/master/Models/LB_Score/deezer_poster2.png)

