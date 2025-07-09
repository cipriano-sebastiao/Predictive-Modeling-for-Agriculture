# Predictive-Modeling-for-Agriculture

Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

A farmer is looking for assisstance in selecting the best crop for his field using machine learning techniques. They've provided me with a dataset called soil_measures.csv, which contains:

- "N" : Nitrogen content ratio in the soil
- "P": Phosphorous content ratio in the soil
- "K": Potassium content ratio in the soil
- "pH" value of the soil
- "crop": categorical values that contain various crops (target variable).
Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the "crop" column is the optimal choice for that field.

In this project, I will build multi-class classification models to predict the type of "crop" and identify the single most importance feature for predictive performance.
