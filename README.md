![EDA_and_Visualization_Project](https://user-images.githubusercontent.com/105673165/185550050-f0a45a6e-a2e2-42db-8771-09c52e317e51.png)

# Superstore Sales Exploratory Data Analysis - dataset available at:
  - https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting
  
    *It's a dataset with 9800 sales records over 4 years.

## This is my first data science project - an Exploratory Data Analysis & data Visualization.
  *Please, to check an ideal notebook, i recommend you to open the repository link in NBViewer (https://nbviewer.org/), 
  since i implemented an interactive Plotly chart in this notebook - does not work ideally with GitHub.
  

### We have some questions to guide our exploration:
  - How were the sales at the analyzed period?;
  - Which was the most sold category of products?;
  - Which was the top selling product?;

#### The libraries i utilized were:
  - pandas
  - numpy
  - matplotlib.pyplot
  - datetime
  - plotly.graph_objects

*---------------------------------------------------------------------------------------------------------------------------------*
#### I started treating null values, creating new data features and removing undesired data.

So, moving on to the analysis itself...

  - We evaluated all the data related to the sales:
    - Assessed the business revenue over the entire data period;
    - Observed a potential trend in sales and orders numbers increase and a sales seasonality within the years;
    ![output_20_0](https://user-images.githubusercontent.com/105673165/185568143-c841675a-13c1-42e8-94ab-eaff970f8742.png)
    ![output_22_0](https://user-images.githubusercontent.com/105673165/185568160-f3cec831-76ef-45b6-aeb3-c8cefd829969.png)
    
    - Defined our customers favourite ship mode (Standard);
    - Observed a possible business logistic pain point in Days To Ship (max DTS of seven days - to start the shipping!);
    ![output_24_0](https://user-images.githubusercontent.com/105673165/185569058-db542fb5-3eb1-44c4-a5ef-40700cdfb802.png)
    ![output_26_0](https://user-images.githubusercontent.com/105673165/185569088-113e6c3b-bc27-4793-8413-e4a9df54626a.png)
    
    - Characterized the sales over the entire country, by different regions, states and cities;
    - Giving us marketing and logistic insights to work with, like raise the propaganda in lower sales regions;
    ![output_34_0](https://user-images.githubusercontent.com/105673165/185570044-e4001b5b-f4bd-46b3-9e5e-5b43dade9810.png)
    ![image](https://user-images.githubusercontent.com/105673165/185569571-68158ff6-5a40-406b-a553-e1af06045994.png)
    ![output_40_1](https://user-images.githubusercontent.com/105673165/185571279-e23ff3ba-86d2-4576-b644-efaed651ae80.png)

    - The category with the biggest revenue is Technology, but the most ordered one is Office Supplies;
    ![output_42_0](https://user-images.githubusercontent.com/105673165/185571953-d30db6ec-5aaf-491b-a8e5-fdb4bcac383c.png)
    ![output_42_1](https://user-images.githubusercontent.com/105673165/185571978-9eb10960-f701-4fc9-8e21-593e34ce6d9b.png)

    - And the specific product with the biggest revenue is a Canon Copier, while the most ordered products are Staple Envelope, Staples and Easy-staple paper.
    ![output_48_0](https://user-images.githubusercontent.com/105673165/185572413-88e9b7e3-667e-471a-919d-298e4f9493d1.png)
    ![output_50_0](https://user-images.githubusercontent.com/105673165/185572428-e254ce0c-050a-4ff8-b932-4eb3b70d7b31.png)

*---------------------------------------------------------------------------------------------------------------------------------*

## Next steps:
### Since we already answered these questions, our work here would be finished. But we can go further and build a model to forecast the sales in the future. That model would use the sales behavior in the observed data, like trend and seasonality, to predict the behavior of this variable in an upcoming period. But this will be for another time.
