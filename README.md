# Predict Customer Personality to Boost Marketing Campaign by using Machine Learning

## Overview
Sebuah perusahaan dapat berkembang dengan pesat saat mengetahui perilaku customer
personality nya, sehingga dapat memberikan layanan serta manfaat lebih baik kepada customers
yang berpotensi menjadi loyal customers. Dengan mengolah data historical marketing campaign
guna menaikkan performa dan menyasar customers yang tepat agar dapat bertransaksi di
platform perusahaan, dari insight data tersebut fokus kita adalah **membuat sebuah model
prediksi kluster sehingga memudahkan perusahaan dalam membuat keputusan**.

## Dataset
Dataset yang digunakan adalah Marketing Campaign Data yang sebenarnya berasal link Kaggle [berikut](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign) yang telah dimodifikasi untuk keperluan mini project ini oleh tim Rakamin. Berikut adalah deskripsi dari tiap kolomnya
- `ID` : Customer's id
- `Year_Birth` : Customer's year of birth
- `Education` : Customer’s level of education
- `Marital_Status` : Customer’s marital status
- `Income` : Customer’s yearly household income
- `Kidhome` : Number of small children in customer’s household
- `Teenhome` : Number of teenagers in customer’s household
- `Dt_Customer` : Date of customer’s enrolment with the company
- `Recency` : Number of days since the last purchase
- `MntCoke` : Amount spent on coke products in the last 2 years
- `MntFruits` : Amount spent on fruits products in the last 2 years
- `MntMeatProducts` : Amount spent on meat products in the last 2 years
- `MntFishProducts` : Amount spent on fish products in the last 2 years
- `MntSweetProducts` : Amount spent on sweet products in the last 2 years
- `MntGoldProds` : Amount spent on gold products in the last 2 years
- `NumDealsPurchases` : Number of purchases made with discount
- `NumWebPurchases` : Number of purchases made through company’s web site
- `NumCatalogPurchases` : Number of purchases made using catalogue
- `NumStorePurchases` : Number of purchases made directly in stores
- `NumWebVisitsMonth` : Number of purchases made through company’s web site
- `AcceptedCmp3` : 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- `AcceptedCmp4` : 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- `AcceptedCmp5` : 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- `AcceptedCmp1` : 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- `AcceptedCmp2` : 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- `Complain` : 1 if customer complained in the last 2 years
- `Z_CostContact` : Cost to contact a customer
- `Z_Revenue` : Revenue after client accepting campaign
- `Response` : 1 if customer accepted the offer in the last campaign, 0 otherwise