This project turns raw Crunchbase-style startup data into actionable insight through a full data science pipeline
— from cleaning to prediction to segmentation. I engineered a classification pipeline (Logistic Regression, Random Forest) 
to predict a startup's outcome — operating, acquired, or closed — while addressing class imbalance with SMOTE. 
In parallel, I built a regression pipeline (Linear Regression, Random Forest Regressor) to estimate total funding
raised based on company attributes, evaluated using RMSE and R². To uncover hidden structure in the data, 

I applied KMeans clustering, using the elbow method to identify three distinct startup funding profiles. 
The result is an end-to-end analysis combining exploratory visualization, predictive modeling,
and unsupervised learning to understand what drives startup success and funding behavior
