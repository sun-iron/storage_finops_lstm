# LSTM model for Storage Budget prediction PinOps
This source code is data from a research paper by sunpark (sunpark@soongsil.ac.kr) titled "Research on Storage Service Operation Models and Cost Prediction by Service Type for Cloud Cost Optimization"

## 1. Why PinOps
Many cloud migration systems are considering abandoning the cloud due to budget overruns, after using it like a legacy environment.
To prevent this situation, we are looking to implement an enterprise-wide cost management system using FinOps (https://www.finops.org/).

## 2. Why Storage
Storage usage costs may seem negligible initially, but they accumulate over time.
Service-related files, rather than simple files, will lead to cost pressure once they accumulate.
Therefore, storage costs require careful planning from the beginning.

## 3. What to do
It’s quite simple:

1. Classify the data stored in the storage.
2. Study the characteristics of cloud storage.
3. Design the batch model according to the data characteristics.
4. Continuously predict the budget trends using machine learning.

![image](https://github.com/user-attachments/assets/1bbf3649-3977-49bf-bad3-6e88c7db2d8a)
