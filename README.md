# Fulfillment by Amazon proposal
>Our model will predict the high chances of ratings for various product classes to help fulfillment centers prioritize products in their inventories. 
>* We are correlating high customer ratings with high purchase probability.

## Approach 
* **DATASET:**
  > Amazon Product's Ratings and Reviews as per their details listed on the official website of Amazon 
  > * **Link:** https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset 
  > * **file name:** amazon.csv 
  
* **DESCRIPTION:**
  >This dataset has the data of 1K+ Amazon Product Ratings and Reviews as per their details listed on the official website of Amazon

* **ANALYSIS:** 
  >1. **Data Collection**
  > - Gather historical ratings, sales data, and product features.
  >2. **Data Preprocessing**
  > - Clean and prepare data for analysis.
  >3. **Feature Engineering**
   >- Identify and create relevant features that influence customer ratings.
  >4. **Model Training**
   >- Use machine learning algorithms to train the model on historical data.
  >5. **Prediction**
   >- Generate predicted ratings for current and new products.
  >6. **Evaluation**
   >- Validate model accuracy using test data and performance metrics.

* **Data preprocessing:**
  >* **Setup:** 
  >   * create a `gitconfig.py` file in your repository and set your environment path in the file to `env_path = "repository path\Resources"`
  >* **Data exploration:**
  >   * The dataPreprocessing.ipynb file reads the amazon.csv file. Make sure you are using the correct path in the **setup** steps above
  >  * **Models used:** Models can be viewed in our respective branches (adedapo,randon,shubhda,alfredo) We experimented with several models `Logistic Regression`, `Random Forest` and `Gradient Boosting` but settled on `Gradient Boosting` as it gave us the highest Accuracy score of 99%


# Summary
>In our data we were able to plot the distribution of customer ratings over our product catalog and discovered over 50% of our products get high ratings and thus prioritizing our inventory to fulfilling those products would yield profitability. In addition high product ratings also are highly recommended by customers.
![alt text](image-1.png)
Our model was used for our FBA presentation which can be found here https://docs.google.com/presentation/d/1MvuZbV2OCLTtOaXoCHrrSdW9vhhCNEoYyEaxC3sZ1Xc/edit#slide=id.g2fdbb8424f2_0_0