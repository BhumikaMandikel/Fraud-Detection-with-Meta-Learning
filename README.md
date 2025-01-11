# Fraud-Detection-with-Meta-Learning
This project uses the **Meta-Learning Reptile** algorithm for financial fraud detection. Traditional machine learning models struggle to adapt to dynamic fraud patterns, especially with limited labeled data. By leveraging Reptile, a first-order gradient-based meta-learning algorithm, this approach rapidly adapts to new fraud data, improving detection accuracy and robustness.
We have reduced all our datasets to have 32 attributes responsible for the output feature which  determines if the transaction is fraudulent or not using PCA.These reduced datasets have been provided.
It is important for all the datasets to be of similar size for easier adaptation of model.

## Key Features
- **Meta-Learning with Reptile**: Optimizes model initialization to quickly fine-tune on new fraud datasets.
- **Enhanced Generalization**: Outperforms conventional methods by better generalizing across various fraud scenarios.
- **Scalable and Robust**: Handles evolving fraud patterns with minimal data, making it ideal for real-world deployment in financial systems.

