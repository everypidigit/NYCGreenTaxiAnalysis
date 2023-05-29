# NYCGreenTaxiAnalysis

## This project is an exploratory data analysis of NYC Green Taxi Rides dataset from July 2022. Available at: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

### After exploring dataset, I train 4 machine learning models, 
including Random Forest Regressor, Histogram Gradient Boosted Trees Regressor, Gradient Boosted Trees Regressor, and XGBoost regressor, to predict the trip length depending on 17 other features.

### Taking numerical and categorical columns, 
I impute missing values using different techniques and pack all the preprocessing in a sklearn pipeline. I then train and test all of the models on this pipeline, measuring MAE for each.

### After that, I use cross-validation with 5 folds to try to increase performance (=decrease MAE). It works well: RFR's performance gets better by ~40%.

Then, I try shuffled cross-validation, which does not increase performance, only worsens it. 

#### If you have any inquiries or questions, feel free to contact me on LinkedIn (everypidigit) or by email: everypidigit@gmail.com
