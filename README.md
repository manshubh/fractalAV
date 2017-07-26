# Fractal Analytics Vidhya Hackathon
Fractal Analytics Hiring Hackathon 2017 - RMSE Score : 0.711622 (Top 100)

# Problem Statement
Welcome to Antallagma - a digital exchange for trading goods. Antallagma started its operations 5 years back and has supported more than a million transactions till date. The Antallagma platform enables working of a traditional exchange on an online portal. 

On one hand, buyers make a bid at the value they are willing to buy ("bid value”) and the quantity they are willing to buy. Sellers on the other hand, ask for an ask price and the quantity they are willing to sell. The portal matches the buyers and sellers in realtime to create trades. All trades are settled at the end of the day at the median price of all agreed trades. 

You are one of the traders on the exchange and can supply all the material being traded on the exchange. In order to improve your logistics, you want to predict the median trade prices and volumes for all the trades happening (at item level) on the exchange. You can then plan to then use these predictions to create an optimized inventory strategy. 

You are expected to create trade forecasts for all items being traded on Antallagma along with the trade prices for a period of 6 months. 

Evaluation Criteria: 
Overall Error = Lambda1 x RMSE error of volumes + Lambda2 x RMSE error of prices Where Lambda1 and Lambda2 are normalising parameters.


# Data
## Variable	Definition
* ID : Unique_transaction_ID
* Item_ID  :	Unique ID of the product
* Datetime :	Date of Sale
* Price  :	Median Price at Sale on that day(Target Variable_1)
* Number_Of_Sales  :	Total Item Sold on that day(Target Variable_2)
* Category_1 :	Unordered Masked feature
* Category_2 :	Ordered Masked feature
* Category_3 :	Binary Masked feature
