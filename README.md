## Credit Card Fraud Analysis
Analysis of credit card fraud data.

## Dataset

The datasets contains credit card transactions over a two day collection period in September 2013 by European cardholders. There are a total of 284,807 transactions, of which 492 (0.172%) are fraudulent.

The dataset contains numerical variables that are the result of a principal components analysis (PCA) transformation. This transformation was applied by the original authors to maintain confidentiality of sensitive information. Additionally the dataset contains `Time` and `Amount`, which were not transformed by PCA. The `Time` variable contains the seconds elapsed between each transaction and the first transaction in the dataset. The `Amount` variable is the transaction amount, this feature can be used for example-dependant cost-senstive learning. The `Class` variable is the response variable and indicates whether the transaction was fraudulant.

_Note:_ The data file is no longer made available in this code repository. It is available in the Docker container or the [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) Kaggle competition.
