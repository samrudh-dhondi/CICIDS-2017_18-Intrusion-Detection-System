
# CICIDS 2017_18 Intrusion Detection System

A deep learning-based intrusion detection system that can detect network threats and anomalies using the CICIDS2017_18 datasets. This system is designed to accurately detect various network threats, such as DDoS, brute force, infiltration, and botnet attacks, by leveraging deep learning techniques. The dataset provides a comprehensive and labeled collection of network traffic data, making it ideal for building and evaluating intrusion detection models.

### Methodology
- Data Loading: Import the CICIDS2017 dataset into a Pandas DataFrame.
- Data Cleaning: Remove duplicate rows to ensure unique training instances. Drop columns with all-zero values to reduce noise and computational cost.
- Data Preprocessing: Applied EDA for preprocessing
- Dimensionality Reduction: Use PCA to retain 95% variance and remove irrelevant features.
- Model Training: Trained using various Machine Learning Algorithms and Deep Learning Model (CNN + MLP)
- Results: The CNN-MLP, in comparison with the traditional models, gave a test accuracy of 94.8% 


## Evaluation

![graph](https://github.com/user-attachments/assets/2aca3231-5b4b-4863-b057-0576c0f37249)

![precison recall f1 bar](https://github.com/user-attachments/assets/84182b16-c324-41ec-8e72-83fe3f108987)

