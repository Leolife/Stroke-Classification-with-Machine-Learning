# Stroke Classification with Machine Learning

Dataset used: https://www.kaggle.com/datasets/godfatherfigure/healthcare-dataset-stroke-data

Results: [Results with discussion](Final-Results/Results.ipynb)

## Process
- analyzed dataset to discover heavy imbalances and a difference in importance across variables
- used SMOTE to balance the dataset and used feature creation through combining other features
- Tested numerous models using many different SMOTE ratios and visualized results
### Results
- Bagging model resulted a high accuracy of 98.83%, and a high f1 score of 0.91 indicating an overall balance of good results with account for accuracy and recall
