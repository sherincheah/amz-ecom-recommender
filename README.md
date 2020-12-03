# Amazon E-Commerce Recommendation System Using Content-Based Filtering

## Problem Statement
When shopping on E-commerce platforms, customers may be faced with a bunch of irrelevant recommended products which could possibly divert them out from the shopping platform. Possible reasons include the suggested product price is beyond their budget and item style is too different. Understanding consumer preferences and leveraging on it to retain them in the site could increase the likelihood of them purchasing an item.

## Objectives
To recommend users a list of similar products in the same category based on the current product they are browsing.

## Installation & Usage
1) Download [amazon products dataset](https://github.com/sherincheah/Ecommerce-recommendation-system/blob/main/amazon%20products.csv). Because the file is too large Github only shows in raw format. You will see "Raw" button on the top right side of the dataset, press "Alt" and then left click the "Raw" button. The whole CSV will download in your system. To convert from txt to csv file, open Excel, under Data tab click on 'From Text' to upload the txt file.
2) There are 2 files containing codes - Data Cleaning with EDA and Algorithms only.
3) Open python codes on a compatible platform eg. jupyter notebook, google colab 

## Methods 
- Recommendation system part I: Product popularity based system targeted at new customers<br />
- Recommendation system part II: Model-based collaborative filtering system based on customer's purchase history and ratings provided by other users who bought items similar items<br />
- Recommendation system part III: When a business is setting up its e-commerce website for the first time without any product rating<br />

![cold start reco](https://user-images.githubusercontent.com/58731785/100766577-c2234580-3433-11eb-8d19-0cedd6f14b49.png)

## Algorithms 
![tfid ss](https://user-images.githubusercontent.com/58731785/100896683-d893d480-34f9-11eb-8b43-7889650cf105.JPG)
![linear_kernel](https://user-images.githubusercontent.com/58731785/100897061-42ac7980-34fa-11eb-9147-228de7aece8b.JPG)

## Further Work
- Arrange recommended list in ascending order of price so that users will know that is the next best alternative
- Explore into online supermarket recommendation system
  e.g. customer browsing for pastas, there will be 2 categories of recommended list - 'similar products' and 'other related products'

## Authors
- [Sherin](https://github.com/sherincheah)
- [Denzel](https://github.com/bub28)
- [Jesslyn](https://github.com/jesslynhillary)
- [Xiangfeng](https://github.com/xiangfengg)

## Resources
- https://medium.com/datadriveninvestor/how-to-build-a-recommendation-system-for-purchase-data-step-by-step-d6d7a78800b6
- https://data.world/promptcloud/amazon-product-dataset-2020/workspace/file?filename=marketing_sample_for_amazon_com-ecommerce__20200101_20200131__10k_data.csv%2Fhome%2Fsdf%2Fmarketing_sample_for_amazon_com-ecommerce__20200101_20200131__10k_data.csv
