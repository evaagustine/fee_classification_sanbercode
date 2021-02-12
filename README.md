# fee_classification_sanbercode
My first own project for final project assignment according to Sanbercode Data Science course. I've build a machine learning for job fee classification, it was published in Kaggle Competition Sanbercode Data Science 0620.

So, at first the aim of the project is to predict the label for column "Gaji" or we can call it fee in english. The label is 0 and 1, where 0 means Gaji <= 7 million and 1 means Gaji > 7 million.

## Without further do, here is the step!
1. Input the data that already provided by Sanbercode called train.csv and test.csv
2. Pre-processing data for both train and test
  a. Inputing missing value for categorical nominal data with mode
  b. Encode data for categorical ordinal data
3. Tuning hyperparameter with gridsearch cv
4. Build machine learning with Decision Tree Regressor algorithm
5. Save the prediction in excel and its done!

The accuracy evaluate with cross validation is 95% which is pretty good after a bunch of tries, what I learned that time was we should choose the right machine learning algorithms to get a good accuracy score, I mean in that time I just realized how important to know the basic about supervised and unsupervised learning. I know its sounds very simple and easy but at first it gives me such a struggle. But it was so much fun for my first learn about machine learning! :)
