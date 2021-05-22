![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Project: Visualizing Real World Data - Women's Shoe Prices

## Overview

The goal of this project was to practice creating and interpreting different types of visualizations using real world data.

I have chosen to study a 2019 dataset of around 19,000 women's shoes and their associated product information. The dataset is the public extract of one of the databases sold by Datafiniti, a database provider. The public extract was downloaded from Kaggle.

Each line of the dataset is a pair of shoes sold at a merchant website. It shows description, brand, price, merchant and more.

Although it is a big dataset, a lot of information appears to be missing or non-usable, which made for long data cleaning at the beginning of the project. We only kept 725 rows and 6 columns from an initial dataset of 19,045 rows and 47 columns.

I have focused on studying the potential links between price and brand, and between price and color.



## Technical info

 - The dataset used was uploaded at https://www.kaggle.com/datafiniti/womens-shoes-prices?select=7210_1.csv
 - The codebook for the dataset can be found at https://developer.datafiniti.co/docs/product-data-schema
 

## Necessary Deliverables

 - A gitHub repo was created specifically for this project, and can be consulted at https://github.com/HH2805/M2-mini-project-Dataviz-Helene
 The repo includes:
 --- A Jupyter notebook, named 'Shoes_Data-Viz_preparation'.
 - A Tableau workbook was created and can be found at: https://public.tableau.com/profile/h.l.ne.hill#!/
 It shows some graphs and insight.

## Insights

Which shoe brands are the most expensive? 
How much does a typical pair cost?
Does color and/or brand influence the price of shoes?

## Conclusion & Going Further

It would have been useful to have a more complete dataset to study. I suspect that brand and color may not be the most important variables explaining price of shoes.
The project timeframe did not allow to un-nest the info in the 'Shoe Features' column. It would be interesting to do so. I suspect we could find explicative variables there, such as style (pump, peep-toes, sandal etc.), heel height, material (leather or synthetic) to explain the price variable. 
It would be interesting to use the statsmodel library to see which of these variables explain the most the price of a shoe.
Finally, there is another dataset by Datafiniti relating to men's shoes. It would be interesting to study the differences between the 2 datasets to see if there is a difference in price between women and men.
