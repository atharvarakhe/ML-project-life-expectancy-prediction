I request to everyone, wait for few seconds after giving input at,first time when we will give input to it takes 10-15 seconds to get output and and next when we will give input it takes lessthan 5 seconds to get output.
This happens beacause of form should give input to model and it should process it and give output via node-red UI.

# Predicting Life Expectancy With Auto AI

Auto AI is provided by IBM Cloud.
AutoAI automatically runs the Data pre-processing,Automated model selection,Automated feature engineering,Hyperparameter optimization

## Data pre-processing: -
Most data sets contain different data formats and missing values, but standard machine learning algorithms work with numbers and no missing values. AutoAI applies various algorithms, or estimators, to analyze, clean, and prepare your raw data for machine learning. It automatically detects and categorizes features based on data type, such as categorical or numerical. Depending on the categorization, it uses hyper-parameter optimization to determine the best combination of  strategies for missing value imputation, feature encoding, and feature scaling for your data
## Automated model selection: -
The next step is automated model selection that matches your data.  AutoAI uses a novel approach that enables testing and ranking candidate algorithms against small subsets of the data, gradually increasing the size of the subset for the most promising algorithms to arrive at the best match. This approach saves time without sacrificing performance.  It enables ranking a large number of candidate algorithms and selecting the best match for the data.
## Automated feature engineering: -
Feature engineering attempts to transform the raw data into the combination of features that best represents the problem to achieve the most accurate prediction. AutoAI uses a unique approach that explores various feature construction choices in a structured, non-exhaustive manner, while progressively maximizing model accuracy using reinforcement learning. This results in an optimized sequence of  transformations for the data that best match the algorithms of the model selection step.
## Hyperparameter optimization: -
Finally, a hyper-parameter optimization step refines the best performing model pipelines. AutoAI uses a novel hyper-parameter optimization algorithm optimized for costly function evaluations such as model training and scoring that are typical in machine learning. This approach enables fast convergence to a good solution despite long evaluation times of each iteration.
