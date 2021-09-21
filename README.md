## Anomaly Detection Credit Card with Gaussian Mixture

![Credit-cards](https://user-images.githubusercontent.com/36668856/134003736-bd626894-70ab-4190-a55e-4867c8c01cb4.jpeg)

## Introduction

### Case = Anomaly Detection (Unsupervised Model)

#### Dataset
Dataset berisi transaksi yang dilakukan dengan kartu kredit pada bulan September 2013 oleh pemegang kartu Eropa. Dataset ini menyajikan transaksi yang terjadi dalam dua hari, dimana kami memiliki 492 penipuan dari 284.807 transaksi. Dataset sangat tidak seimbang, kelas positif (penipuan) menyumbang 0,172% dari semua transaksi.

#### Sumber dataset
Dataset berasal dari kaggle dengan link : https://www.kaggle.com/mlg-ulb/creditcardfraud

#### Objectivitas
melakukan anomaly detection pada transaksi kartu kredit

## Library
- pandas
- numpy 
- matplotlib
- seaborn 

#### Pre-processing
- StandardScaler
- PCA

#### Model
- GaussianMixture

## Exploratory Data Analysis

#### Visualisasi konsumen yang melakukan Fraud

![class_feature](https://user-images.githubusercontent.com/36668856/134098594-9c24f252-5fa5-4357-8f24-e5d13f86793f.png)

#### Visualisasi Waktu Transaksi kejadian Fraud

![time_fraud](https://user-images.githubusercontent.com/36668856/134098750-d7424ef1-5627-49e4-a61c-302c772a2ecb.png)

#### Visualisasi Nilai kejadian fraud

![value_fraud](https://user-images.githubusercontent.com/36668856/134098789-0de48043-d88e-4369-8511-d92f314b753f.png)

## Fit and Training Model

![training fitmodel](https://user-images.githubusercontent.com/36668856/134098852-90979701-b811-4b00-8c0f-f98552337429.png)

## Evaluation Model

![evaluation_model](https://user-images.githubusercontent.com/36668856/134098892-cf4464e8-a6cf-4f76-b581-60835456de21.png)

## Visualisasi Persebaran Data

#### Visualisasi Persebaran Data

![persebrandata](https://user-images.githubusercontent.com/36668856/134098986-7a7a8ac2-9650-490a-b316-d083405bf041.png)

#### Visualisasi Anomaly Data

![persebaran_anomaly](https://user-images.githubusercontent.com/36668856/134099031-e3b4f120-18d9-4bcf-9a8d-e4ad40d969e3.png)

## Model Inference

melakukan prediksi dengan menggunakan data baru

![model_inference](https://user-images.githubusercontent.com/36668856/134099087-acd121f1-7732-4e7c-8842-ec358f742899.png)


