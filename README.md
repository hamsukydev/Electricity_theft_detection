## About Dataset
## Overview
The State Grid Corporation of China (SGCC) dataset with 1000 records was used in the
model. This is a key resource in the field of power distribution and management, with a large and
varied set of data about electricity transport and grid operations. This set of data contains a lot of
different kinds of information, such as history and real-time data on energy use, grid
infrastructure, the integration of green energy, and grid performance. It is a key part of making
power distribution networks more reliable and efficient by helping with things like predicting
demand, watching the grid, and finding problems. Researchers, energy providers, and law-
makers can use this information to learn important things about electricity usage trends, the
health of the grid, and the merging of green energy sources. This will help the electric power
industry come up with new strategies and ideas that are based on data.

## Description
Electricity theft detection released by the State Grid Corporation of China (SGCC) dataset data set.csv contains 1037 columns and 42,372 rows for electric consumption from January first 2014 to 30 October 2016. SGCC data first column is consumer ID that is alphanumeric. Then from column 2 to columns 1036 daily electricity consumption is given. Last column named flag is the labels in 0 and 1 values. the small version of the dataset datasetsmall.csv only contains the electric consumption for January 2014.

## Features
'MM/DD/YYYY': The electric consumption on a given day .
CONS_NO: Consumer Number stands for a customer ID of string type.
FLAG: 0 indicating no theft and 1 for theft.

## Useful for
Binary Classification: The main intention of the dataset is for binary classification of electrical theft.
Imbalanced Datasets Processing: Useful for exploring class balancing methods.
Time Series Forecasting: Can be used for forecasting and predicting electrical consumption on a given day.

## Notes
This Dataset Contains missing values .
This Dataset has dates of the form MM/DD/YYYY.
This Dataset requires slight cleaning.

## THE PROPOSED SYSTEM ARCHITECTURE
### Introduction
 In conducting research, it is essential to conduct a systematic examination or survey of the existing system. This involves comprehending the processes, procedures, and key problem areas of the current system to precisely identify the tasks that need to be carried out and the appropriate methods for achieving them. This comprehensive understanding of the system's functioning is crucial for the researcher.
 
 ## Proposed System Model
  Our proposed solution for Meter theft detection (MTD) is presented in Figure 1. The proposed system model consists of five parts: 
Data pre-processing
Data balancing
Feature extraction
Classification
Validation

After which the model will be save and further use in the feature

### 
figure 1 Proposed system model.![Picture1](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/b4c4091d-10c7-4955-9ecd-270876904da6)
plot 2. Electricity consumption pattern of thieves and honest consumers () ![Picture2](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/80f1773c-66d4-43a4-8f22-20002200fc56)
plot 3. Generating of synthetic data through SMOTE ![Picture3](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/632d6f78-dc9a-4af6-85ce-f5923371f2ea)
plot 4. the unbalanced and balanced distribution of labels ![Picture4](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/3562705f-8b27-4004-bfe5-600faca17b5b)
plot 5 The Adasyn method improved the performance of the FA-XGBoost classifier. It achieves 93% precision, 97% recall, 93.7% F1-score, and the 95.9% ROC curve. ![Picture5](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/e66fa628-0ca1-412c-9ef0-c24b74f1c075)
plot 6  ![Picture 6](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/ea084a96-9aa1-4cb5-870d-976b05df8c62)
plot 7 Performance comparison of parameter tuning.  ![Picture7](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/24167411-c334-486e-ba19-96c2544c74e3)
plot 8  Accuracy and loss of VGG-16 ![Picture8](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/fd74474d-7f92-4dec-889c-5f7b1b1325b7)
plot 9 Performance metrics comparison with benchmark schemes.  ![Picture9](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/bc52cd79-6470-47b7-9b78-a16d3d88aef2)
plot 10 ROC-AUC of benchmark models. ![Picture10](https://github.com/hamsukydev/Electricity_theft_detection/assets/97235843/ced4c87f-afc7-4365-9b9c-911fce555a37)
