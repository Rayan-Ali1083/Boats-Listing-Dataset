# Boats-Listing-Dataset
This project was used in a seminar for IEEE in FAST-NUCES university. The dataset contains information about boats such as their types, price in various currencies, etc. The target variable was Number of views last 7 days
# Description
## Preprocessing
- Converted the price to same unit
- Split the type to fuel type and condition(later map these to new and used boats)
- Split the location to  country and city
- If a country is not listed , replace it with unknown
- Detect and remove the outliers
- Used standardScaler to scale data
# Visualization
- Used scatterplot to get the frequence of all type of boats
- Later used bar-plot to visualize the fuel type boats (used and new)
- Visualize frequency of known and unknown type
- Visualize the materials used in boats
# Model
- Used Xgboost as model to predict the next 7 days views to boats
