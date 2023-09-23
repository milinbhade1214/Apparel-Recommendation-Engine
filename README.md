# Apparel-Recommendation-Engine
Apparel Recommendation Engine based on Product Title Feature
# Introduction and Problem Statement
<hr>
#### Build a recommendation engine which suggests similar products to the given product in any e-commerce websites using NLP techniques for Text Semantics based product similarity and deep learning techniques for deep learning based visual product similarity.
<hr>
This GitHub repository contains the code and documentation for building an apparel recommendation engine that leverages various natural language processing (NLP) and deep learning techniques. The core idea behind this project is to recommend apparel items to users based on the titles of the products they are interested in. We utilize BOW(Bag of Words), TF-IDF,  Word2Vec embeddings, CNN (Convolutional Neural Networks) to extract meaningful features from product titles and calculate similarities for personalized recommendations. Visualizations are used to get sense of how similar are the products that are recommended given some query product.


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
