# Ad_Campaign_performance_project
## Business Objective
  The main objective of this project is to test if the ads that the advertising company runs resulted in a significant lift in brand awareness.
## Project Overview
  SmartAd is a mobile first advertiser agency. It designs Intuitive touch-enabled advertising. It provides brands with an automated advertising experience via machine learning and   creative excellence. Their company is based on the principle of voluntary participation which is proven to increase brand engagement and memorability 10 x more than static         alternatives. 
  SmartAd provides an additional service called Brand Impact Optimiser (BIO), a lightweight questionnaire, served with every campaign to determine the impact of the creative, the   ad they design, on various upper funnel metrics, including memorability and brand sentiment
  As a data scientist in SmartAd, in this project i will be designing a reliable hypothesis testing  algorithm for the BIO service and determine whether a recent advertising         campaign resulted in a significant lift in brand awareness.
## Skills implemented in the project:
* Statistical Modelling
* Using core data science python libraries pandas, matplotlib, seaborn, scikit-learn 
* Linear regression
* Decision Trees 
* XGBoost


## Knowledge implemented in the project:
* Data exploration
* Hypothesis testing
* Machine learning 
* Hyperparameter tuning
* Model comparison & selection
* experiment analysis

## Data
- The BIO data for this project is a “Yes” and “No” response of online users to the following question


Q: Do you know the brand SmartAd? 

		1. Yes
		2.  No
## Dataset Column description
* **auction_id:** the unique id of the online user who has been presented the BIO. In standard terminologies this is called an impression id. The user may see the BIO questionnaire but choose not to respond. In that case both the yes and no columns are zero.

* **experiment:** which group the user belongs to - control or exposed.

* **date:** the date in YYYY-MM-DD format

* **hour:** the hour of the day in HH format.

* **device_make:** the name of the type of device the user has e.g. Samsung

* **platform_os:** the id of the OS the user has. 

* **browser:** the name of the browser the user uses to see the BIO questionnaire.

* **yes:** 1 if the user chooses the “Yes” radio button for the BIO questionnaire.

* **no:** 1 if the user chooses the “No” radio button for the BIO questionnaire.
