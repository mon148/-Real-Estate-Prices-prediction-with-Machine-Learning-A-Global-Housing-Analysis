# -Real-Estate-Prices-prediction-with-Machine-Learning-A-Global-Housing-Analysis
Building a Machine Learning model that can predict global real-estate prices
## Project Background and Objective
House prices vary alot and real-estate investors, agents, clients, and even renters find it difficult to know if a house price is fair and also struggle to estimate house prices/rent accurately in new areas due to many factors like lack of transparency, consistency and data-driven evaluation.Imagine knowing the true value of a property before the seller even speaks.
Imagine avoiding overpricing, underpricing, and bad investment decisions — all with one prediction model. today, i will show you the model i build which is able to predict real estate prices that would help you in buying, selling and investing in real-estate globally.

## This project aims to predict real estate prices using machine learning techniques.
The workflow follows the standard data science pipeline:
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Model Building using Random Forest
Hyperparameter Tuning
Model Evaluation
Feature Importance Interpretation

**Looking into the project starting with the data cleaning and explaratory data analysis**
**Why should i recomend this project as inevitable must own project?! There are some business problems from the rell-estate inventment part which individual also partake in and mosly got affected**

Property price drivers differ across countries (US vs UK vs Dubai vs Europe).
No global standard valuation method.
Buyers risk overpaying due to market opacity.
Agents spend time guessing instead of analyzing.
Developers struggle to forecast ROI in new regions.
Investors cannot compare cities easily (NY vs London vs Dubai vs Lagos).

**Globally, billions are lost because of poor or inconsistent valuation method in terms of international or Global house pricing and investment**

**What this precision price prediction is capable of**

 Cross-country comparison of investment opportunities
Better pricing decisions for buyers, sellers, and investors
Faster valuation process for agencies
Developers can plan projects with more accuracy
Banks can improve mortgage risk assessment
Investors can identify undervalued countries and cities

**The list abpve shows that the quality and the ability or capability of this model is not nbased only on real-estate price alone, but also works for banks, marketers, other companies. Whether it's London, New York, Lagos, or Dubai — a good predictor removes guesswork

**What is the mission of this project?**
**The mission is using Machine Learning model to predicts house prices across different countries using structured features and insights extracted from text.**

**the Dataset has the following**
**over 145k data gotten frrom kaggle and over 19k African data scraped from online real estate platforms**
**Features include price (in USD)`, bedrooms, bathrooms, location, property type, title, etc.**
**Text features extracted from property title include (studio, duplex, penthouse, etc)**
It has a lot more features but in summary, the goal is to take raw, messy real-estate listings and turn them into inteligent insights!


**What i did in the data Cleaning state (i.e. making the data usable)**

**Standardized currency**
**converted price to numeric**
**Extracted features from texts**
**Removed duplicates**
**Filled the important columns that has missing values with the mean**
**Removed Extreme Outliers**
A lot more but to mention few. Over 35% of reson for the cleaning is to ensure the model that would be built using the cleaned data learn from reality not noise

**What i discovered in the exploratoer data analysis stage**
**Property that are furnished has a high premium price**
**City-level differences are larger than country-level differences**
**Aprtment and house really have geat in fluence on the price. i.e, they have the highest listing which is to say, apartment and duplex dominate the market.**
**Extracted text features helped differentiate property types better**

This insights reveal real trends in the global real-estate pricing and they guild the model

**The models that were tested include**
**Linear regression**
**Decision tree**
**Linear regression**
**Random Forest (Baseline)**
**Tuned random forest (optimized)**

multiple models were tested but Random Forest performed best because it manages complex non-linear patterns and interactions between features

**The RMSE of the Random Forest gave out 0.4 and r2 as 0.8 unlike the rest of the models that produces more than 0.45 ad lest than 0.75 of r2 which typically asying in the ML term, the other models apart from RF is yet to the optimims**

**The features that influence the price most are:**
**Location**, **Bedroom**, **Bathrooms**, **Area(extracted from title column)**,
**property type**, **furnisshing**

with these features influencing the price shows the REAL drivers of property vslue. and this ia a powerful business knowledge

**What is the impact this model has on business?**
**Investors can dicover undervalued properties instantly**,
**Cross-border investors can compare different regions fairly**
**Real-estate marketplaces can automatically recommend price ranges to sellers**
**Developers can predict ROI (Return on investment) for different countries**
**Mortgage companies get more accuracy property risk evaluation**
**Whichever agent uses this model enable the clents to trust him/her since they use data-driven pricing**
**Real estate agents can price property accurately before negotiation**
This model is not just a model but a real business tool and the model can be deployed globally — not just for one region

**Global real estate is a gold but without data, we are mining it blindly**
**Using this, i show you how ML can guide smarteer, fater and more profitable decisions**

**There are deployement posibilities which would make it more available for use in the international market place**
**API for real-estate companies
Pricing assistant for agents
Investment decision dashboard
Country comparison tool
Property valuation mobile app
Dynamic pricing engine for listings websites**

**What are the future work to be done on the project to improve it further?**
**Use geo-coordinates instead of text city names
Add satellite imagery
Add economic indicators (interest rate, inflation)
Use deep learning models
Build a global real-estate prediction API**
