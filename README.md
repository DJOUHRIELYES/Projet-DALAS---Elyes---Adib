Research question: The price of a used car depends on many factors: age, mileage, brand, engine type, power, equipment. Our research question is the following: which characteristics of a vehicle best explain its price, and to what extent can it be predicted? We want both to predict the price with the lowest possible error and to identify the variables that truly influence it.

Data: No single dataset contains all the necessary information. We therefore build our own dataset from four sources: the Automobile dataset from the UCI Machine Learning Repository (archive.ics.uci.edu/dataset/10/automobile), and used car datasets found on Kaggle. In each dataset, we keep only the columns useful for explaining the price.
The last dataset (`voitures_occasion_xl.csv`, 200,000 vehicles, 50 columns), too large to be hosted on GitHub, is available on Google Drive: [download the file](https://drive.google.com/file/d/1--6uW6q5nbqFQZBd7IgVmFroS4dTy8cX/view?usp=sharing).

Cleaning: For each dataset, we fix the data types, harmonize labels and units, remove duplicates, handle outliers and missing values, documenting each choice.

Merging. The cleaned datasets are combined into a single final table using common keys.

Modeling: In the first approach, we test several combinations of columns and keep the most relevant one. In the second, we set the columns in advance. We then compare the results of the two approaches.

Our git is in : https://github.com/DJOUHRIELYES/Projet-DALAS---Elyes---Adib
