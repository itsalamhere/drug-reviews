# drug-reviews

# Dashboard of Drug Reviews and Sentiment Prediction

Data science applications in healthcare can offer us a good amount of interesting insights to the stakeholders. Aside from more-advanced applications to health workers to such as predictive analytics, medical imaging, and drug research, data such as customers' sales and reviews in healthcare products can also be used by pharma and medical device companies in evaluating their market or product.

The data has been collected from [drugs.com](drugs.com) and stored in a single CSV file by [Ahmed et al., (2023)](https://data.mendeley.com/datasets/64cc5w5dxy/1) . The dataset contains 392510 unique reviews along with:
- `MedicineName` -- the name of the drug,
- `MedicineFor` -- the condition for which the drug was taken,
- `ReviewDate` -- when the review's posted,
- `UserName` -- who posted the review,
- `IntakeTime` -- how long the drug was taken for,
- `Reviews` -- how the user perceives the drug,
- `ReviewLength` -- how many characters are in the reviews,
- `Rating` -- score by the user, scaled from `1-10`,
- `NumberOfLikes` -- the credibility of the review in the form of likes. 

The project will be divided into 4 main sections:
1. `01-EDA-and-data-cleaning`, where we'll be cleaning the data for future purposes of sentiment prediction and dashboard
2. `02-import-csv-to-postgresql`, where we'll be transferring the cleaned data into PostgreSQL database--a lighter size (for dashboard)
3. `03-drug-reviews-dashboard`, where the data will be interfaced on a Tableau dashboard for a more convenient interface, and lastly
4. `04-sentiment-prediction`, where we're utilizing Deep Learning to predict sentiments towards a product.
