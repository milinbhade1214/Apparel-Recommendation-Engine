# Apparel-Recommendation-Engine
Apparel Recommendation Engine based on Product Title Feature
# Introduction and Problem Statement
<hr>
Build a recommendation engine which suggests similar products to the given product in any e-commerce websites using NLP techniques for Text Semantics based product similarity and deep learning techniques for deep learning based visual product similarity.
<hr>
This GitHub repository contains the code and documentation for building an apparel recommendation engine that leverages various natural language processing (NLP) and deep learning techniques. The core idea behind this project is to recommend apparel items to users based on the titles of the products they are interested in. We utilize BOW(Bag of Words), TF-IDF,  Word2Vec embeddings, CNN (Convolutional Neural Networks) to extract meaningful features from product titles and calculate similarities for personalized recommendations. Visualizations are used to get sense of how similar are the products that are recommended given some query product.
![image](https://github.com/milinbhade1214/Apparel-Recommendation-Engine/assets/43195552/2ac4d4ad-2c11-40ec-836c-530375d996b5)
![image](https://github.com/milinbhade1214/Apparel-Recommendation-Engine/assets/43195552/0cf5beb5-ddd5-4e9d-91f5-9b74e824838b)
![image](https://github.com/milinbhade1214/Apparel-Recommendation-Engine/assets/43195552/9e4e81d3-11ee-4f90-9266-8ad29a3e3da3)
![image](https://github.com/milinbhade1214/Apparel-Recommendation-Engine/assets/43195552/0068e5b1-25e4-4c84-b1bc-7b925f76784a)
![image](https://github.com/milinbhade1214/Apparel-Recommendation-Engine/assets/43195552/866ad75e-e433-4acd-8a0d-eaec7567b111)


## Objective
- The recommendation engine, uses information about 1,80,000 products and each product will have multiple features named.
- We will try multiple techniques using text/title and image to recommend similar products/items
- Each product/item has 19 features in the raw dataset out of these 19 features, we will be using only 6 features

1. asin ( Amazon standard identification number)
2. brand ( brand to which the product belongs to )
3. color ( Color information of apparel, it can contain many colors as a value ex: red and black stripes )
4. product_type_name (type of the apperal, ex: SHIRT/TSHIRT )
5. medium_image_url ( url of the image )
6. title (title of the product.)
7. formatted_price (price of the product)
