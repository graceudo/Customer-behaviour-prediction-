# Customer-behaviour-prediction-
## Predicting customer spending behaviour in streaming services
This project explores customer spending behaviour, churn prediction, and customer segmentation in streaming services using machine learning techniques. The analysis was conducted using the Streaming Service Dataset, which contains customer demographic, subscription, and usage information. The objective was to understand how different factors influence monthly customer spending and to identify patterns in user behaviour.

The project began with supervised learning regression models to predict Monthly Spend. I compared single-feature regression models to determine which numerical variable best predicts spending and evaluated whether linear or non-linear models (such as polynomial regression) provided better fits. I then extended the analysis by incorporating multiple numerical features to assess whether multivariate regression improved predictive performance. To further enhance the model, categorical variables such as gender, region, and payment method were encoded and integrated into more advanced models like Random Forest regression.

Additionally, an Artificial Neural Network (ANN) was developed using all available features to predict monthly spending. Different architectures and hyperparameters were tested to optimize performance and compare results with traditional machine learning models.

Beyond spending prediction, the project also investigated customer churn prediction using classification algorithms, evaluating models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. Finally, unsupervised learning techniques were applied to segment customers based on behavioural patterns. k-Means clustering was used to identify natural groupings within the dataset, and its results were compared with other clustering approaches such as hierarchical clustering to determine the most meaningful customer segmentation strategy.

This project demonstrates the practical application of regression, classification, neural networks, and clustering techniques to analyze user behaviour and support data-driven decision-making in digital streaming platforms.
