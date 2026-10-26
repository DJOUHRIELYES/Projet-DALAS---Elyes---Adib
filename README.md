# Used Car Price Prediction

**Authors:** Elyes DJOUHRI and Adib KAGHOUCHE (Wednesday morning group)

**Research question:** The price of a used car depends on many factors: age, mileage, brand, engine type, power, equipment. Which characteristics of a vehicle best explain its price, and to what extent can it be predicted? We want both to predict the price with the lowest possible error and to identify the variables that truly influence it.

**Data (done):** No single dataset contains all the necessary information, so we build our own from four real datasets found on Kaggle:
1. [Used Car Price Prediction Dataset](https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset) (`used_cars.csv`, 4,009 rows)
2. [Car Price Prediction Dataset](https://www.kaggle.com/datasets/sukhmandeepsinghbrar/car-price-prediction-dataset) (`car_price_dataset.csv`, 10,000 rows)
3. [Honda Used Car Selling](https://www.kaggle.com/code/themrityunjaypathak/car-price-prediction) (`honda_car_selling.csv`, 999 rows)
4. [90,000+ Cars Data From 1970 To 2024](https://www.kaggle.com/datasets/meruvulikith/90000-cars-data-from-1970-to-2024) (`CarsData.csv`, 97,712 rows)

**Next steps (not done yet):**
- **Cleaning:** for each dataset, keep the useful columns, fix data types, harmonize labels and units, remove duplicates, handle outliers and missing values, and document each choice.
- **Merging:** combine the cleaned datasets into a single final table using common keys.
- **Modeling:** in the first approach, test several combinations of columns and keep the most relevant one; in the second, set the columns in advance. Then compare the two approaches.

Our git: https://github.com/DJOUHRIELYES/Projet-DALAS---Elyes---Adib