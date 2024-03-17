# deep-learning-challenge

This project aims to utilize deep learning methods to forecast the outcome of funding applications to Alphabet Soup, a philanthropic organization, by examining historical data. The goal is to uncover patterns that can aid in predicting future successful applications, thus aiding Alphabet Soup in more effectively allocating resources.

The dataset contains various features like APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT, alongside the target variable IS_SUCCESSFUL, denoting the efficacy of fund utilization.

Preprocessing involves excluding non-contributing identifiers like EIN and NAME, with IS_SUCCESSFUL serving as the target variable indicating application success.

The neural network model comprises two hidden layers with 90 and 40 neurons, using relu activations for hidden layers and sigmoid for the output layer. This architecture balances complexity and efficiency, aiming for a predictive accuracy surpassing 75%.

Optimization strategies include adjusting layer depths and neuron counts, exploring diverse activation functions, and refining training durations and preprocessing methods.

The model's performance, including whether it achieved the target accuracy and encountered challenges, is detailed. Despite extensive optimization, maintaining performance above the 75% threshold proved difficult due to issues like overfitting and dataset complexity.

Given the neural network's limitations, a Gradient Boosting Machine (GBM) approach using frameworks like XGBoost or LightGBM is recommended for future exploration due to its robustness, efficiency, and interpretability, particularly with tabular data.

In conclusion, this project illustrates applying deep learning to philanthropic funding prediction, showcasing both its potential and challenges. Exploring alternative models like GBM presents a promising avenue for enhancing predictive accuracy and understanding the factors influencing funding success.
