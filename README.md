# drug-reviews

# Customer Reviews on Drugs Purchasing and Satisfaction

Data science applications in healthcare can offer us a good amount of interesting insights to the stakeholders. Aside from more-advanced applications to health workers to such as predictive analytics, medical imaging, and drug research, data such as customers' sales and reviews in healthcare products can also be used by pharma and medical device companies in evaluating their market or product.

In this project, we'll be exploring the dataset of from Ahmed et al., (2023). The dataset contains 392510 unique reviews along with the name of the drug, user rating, the credibility of the review in the form of likes, length of the reviews, the condition for which the drug was taken and how long the drug was taken for.

The project will be divided into 4 main sections:
1. `01-EDA-and-data-cleaning` *(this one)*, where we'll be cleaning the data for future purposes of sentiment prediction and dashboard
2. `02-import-csv-to-postgresql`, where we'll be transferring the cleaned data into PostgreSQL database--a lighter size (for dashboard)
3. `03-drug-reviews-dashboard`, where the data will be interfaced on a Tableau dashboard for a more convenient interface, and lastly
4. `04-sentiment-prediction`, where we're utilizing Deep Learning to predict sentiments towards a product.
