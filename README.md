I analyzed a credit card transaction dataset to detect fraudulent transactions using machine learning. 
First, I loaded the dataset and checked for missing values, which were not present. The dataset was highly imbalanced, with fraud cases making up only 0.17% of transactions. To address this, I applied random undersampling to balance the classes.

Before training, I standardized the Amount and Time features.
I then split the data into training and testing sets. A Random Forest classifier was trained on the balanced dataset. The model was evaluated using precision, recall, and F1-score. The results showed improved fraud detection compared to an imbalanced model, with recall being particularly important for identifying fraudulent cases. This approach helps in minimizing false negatives while maintaining a reasonable precision level.


link for the dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
