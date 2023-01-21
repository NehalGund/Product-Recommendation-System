![](https://komarev.com/ghpvc/?username=Product-Recommendation-System&style=plastic&label=Repository+Views)
<h1 align="center"> Product-Recommendation-System </h1>
<p align="center">:sparkles: :womans_clothes: :shirt: :dress: :sparkles:</p>
<p align="center">Recommending similar product based on text features.</p>

# A. Project Description
- The use of recommendation systems is now very common in e-commerce companies like Amazon, Flipkart, Myntra, etc.
- In this project, "Bag of Words", "TF-IDF" and "Word2Vec" models are built to recommend a product based on product title text.

# B. Business Objective
- Many people use e-commerce platforms to buy products. When a product is selected, people expect to see similar products.
- A model which can recommend people similar products is our Business Objective.

# C. Constaints
1. Low Latency - In real time within in few nano seconds the model should be able to recommend similar product to people.
2. Speed - We need speedy model not 100% accurate model. So accuracy is not important. 
3. Same product recommendation error - People doesn't like to see same product again and again.
4. Interpretablity is important.

# D. Data Description
- Dataset contains ladies tops fashion of amazon website, initially data has 183k rows and 19 features.
- By cleaning data we brought down the number of data points from 183K to 25K.
- Of these 19 features, we will use only 7 features in this project.
- The description of this dataset is as following:

## Dataset Description :
|No. | Column name | Description |
| :-| :-| :-|
| 1 | asin | Amazon Standard Identification Number |
| 2 | brand | Brand name of the product |
| 3 | medium_image_url  | URL of the product image |
| 4 | product_type_name | Type of the product |
| 5 | color | Color information of the product |
| 6 | title | Title of the product |
| 7 | formatted_price | Price of the product in ($) US Dollar |

# E. Approch
- Titles fairly describe what the product is. 
- We will use the title feature to recommend a product because they are short and informative.
