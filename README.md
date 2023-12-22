# Assignment11.1 Readme

Summary:
A database of 426k mostly used cars was analyzed using the CRISP-DM methodology. This was an exercise in data understanding, preparing, and modeling with the audience being a group of used car dealers interested in fine-tuning their inventory. Regession models were used, validated and compared. 

Key findings:
1) Trucks command higher prices: Truck models and the category as a whole showed many of the strongest positive correlation to price.
2) If its not a truck, make a something with a big engine: The cars which weren't trucks driving price all had big engines too with models like camaros and corvettes are good bets
3) Sedans are out of style: Sedans pulled down prices as well as anything with a smaller engine. 
4) Front wheel drive will drag prices: People are willing to pay more for any other kind of drivetrain. 
5) Mileage is King: Intuitively, the higher the milage, the lower the price. No other variable had a strong correlation to price.
6) Stay away from colors: White is popular while colors such as blue and silver dragged price down.

Methods: After familiarization with the data, the data was cleaned and prepared resulting in a clean dataset of approximately 75k entries which was then modeled in linear, lasso and ridge regression models. The models were then compared with linear and ridge vastly outperforming the linear model. 


