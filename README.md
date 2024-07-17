## Predicting Anaemia from Image Pixels and Hemoglobin Levels
Predicting Anaemia from Image Pixels and Hemoglobin Levels
Dataset Description
This dataset is curated to facilitate the development of machine learning models aimed at predicting anaemia based on hemoglobin levels and color pixel distribution from associated images. Each row in the dataset corresponds to an individual case with various features.

Columns:
Number:
Type: Integer
Description: A unique identifier for each individual case.
Sex:
Type: Categorical (Male, Female)
Description: The sex of the individual.
%Red Pixel:
Type: Float
Description: The percentage of red pixels in the image associated with the case.
%Green Pixel:
Type: Float
Description: The percentage of green pixels in the image associated with the case.
%Blue Pixel:
Type: Float
Description: The percentage of blue pixels in the image associated with the case.
Hb:
Type: Float
Description: Hemoglobin level of the individual, measured in grams per deciliter (g/dL).
Anaemia:
Type: Categorical (Yes | No)
Description: An indicator of anaemia status (1 for anaemic, 0 for not anaemic).
Usage
This dataset can be utilized for:

Developing and testing machine learning models to predict anaemia.
Analyzing the correlation between hemoglobin levels and color pixel distribution in images.
Educational purposes for learning data preprocessing, feature engineering, and model building.
Acknowledgements
Please ensure proper citation if you use this dataset in your research or project. We appreciate your feedback and suggestions for improving the dataset.

Binary Classification Example
The following Python code demonstrates how to train a binary classifier to predict anaemia status based on the provided dataset.

Requirements
pandas
scikit-learn
seaborn
matplotlib

Code is present in main.ipyn file and the dataset is present in dataset.csv
This is binary class classification problem
