# Amazon_Vine_Analysis

## Overview of the project

The purpose of this project is to analyze the paid Amazon Vine program, a service that will allow  manufacturers and publishers to receive reviews of their products in order to determine if there are any biases between Vine members and Non-Vine member's reviews.
We will have access to approximatively 50 datasets and each one of them contains reviews of a specific product, from clothing apparel to wireless products.

### Resources

#### Software

• Python

• PySpark

• Spark

• PostgreSQL

• Google Colaboratory

• Pandas

Amazon Web Services

## Results

### Perform ETL on Amazon Product Reviews

#### Data reading into a DataFrame

<img width="1606" alt="Reading_data_DataFrame" src="https://user-images.githubusercontent.com/107282754/196068295-00861679-d65b-467a-8cd4-b3bc64cd3ef5.png">

#### Data extraction and DataFrame creations

##### Customers_table_DataFrame

<img width="1186" alt="Customers_Table_DataFrame" src="https://user-images.githubusercontent.com/107282754/196068325-98a6950e-c5f6-41c0-9ae3-117d3ea939b4.png">

##### Products_table_DataFrame

<img width="880" alt="Products_Table_DataFrame:Drop_Duplicates" src="https://user-images.githubusercontent.com/107282754/196068339-5603891e-d309-4a66-94ef-1161c056bd6e.png">

##### Review_ID_table_DataFrame


##### Vine_Table_DataFrame

<img width="958" alt="Vine_Table_DataFrame" src="https://user-images.githubusercontent.com/107282754/196068361-d15b7266-7de2-4f2a-ade0-c214de82ea73.png">

POSTGRESQL

<img width="605" alt="RDS_PostgrSQL(1)" src="https://user-images.githubusercontent.com/107282754/196068414-39d4cb87-8fc6-457e-83ee-a65c7cc6bbfe.png">

<img width="601" alt="RDS_PostgrSQL(2)" src="https://user-images.githubusercontent.com/107282754/196068429-840a67d5-dc43-485e-a609-13150b086434.png">

<img width="757" alt="RDS_PostgrSQL(3)" src="https://user-images.githubusercontent.com/107282754/196068470-9b0fdba2-37b0-4ea0-acdc-c829ae6dc688.png">

<img width="803" alt="RDS_PostgrSQL(4)" src="https://user-images.githubusercontent.com/107282754/196068475-12e9be04-3112-4d66-9da4-98e5355a552d.png">


### Bias of Vine Reviews

###### Cleaned_DataFrame

<img width="1607" alt="Cleaned_DataFrame" src="https://user-images.githubusercontent.com/107282754/196499932-3435d359-b32d-4e5a-b144-8ce4df195f67.png">

###### Total_Votes_DataFrame

<img width="1094" alt="Total_Votes_DataFrame" src="https://user-images.githubusercontent.com/107282754/196500074-faeaea33-78f3-422d-a7a4-6c9108dba0a5.png">

###### Percent_Votes_DataFrame

<img width="1331" alt="Filtered_DataFrame_in_Step1" src="https://user-images.githubusercontent.com/107282754/196500359-cadf33ff-f9d2-47df-8f88-314a522a62b6.png">

###### Non_Paid_Dataframe

<img width="1091" alt="Filtered_DataFrame_in_Step2" src="https://user-images.githubusercontent.com/107282754/196500556-84c28209-01b5-4a7f-971d-054cd0cde4e9.png">

###### Vine_Program_Paid_and_Unpaid

<img width="1154" alt="Vine_Program_Paid_Unpaid" src="https://user-images.githubusercontent.com/107282754/196500824-72f639d1-3870-4bbd-9847-26de61898ddd.png">

#### Vine Reviews

<img width="1390" alt="Total_5_Reviews" src="https://user-images.githubusercontent.com/107282754/196501251-1edf854f-5374-49af-a400-fd629caf48f4.png">

Total Vine and Non-Vine reviews: 38010
5 stars Vine Reviews: 65
5 stars Non-Vine reviews: 20612
Percentage of Vine reviews with 5 stars: 38.2%
Percentage pf Non-Vine reviews with 5 stars: 54.5%

## Summary
