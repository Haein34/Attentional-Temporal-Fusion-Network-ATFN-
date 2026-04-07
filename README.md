# ATFN: ESG-Integrated Stock Prediction Model

## Title
Enhancing Stock Prediction through ESG Knowledge Integration for Sustainable Investment

---

## Description
This repository provides the code and datasets for the proposed **ATFN (Attention-based Temporal Fusion Network)** model, integrating ESG sentiment and technical indicators to predict stock market indices (S&P 500 and DJIA).

The framework combines:
- ESG sentiment extracted from news articles  
- Financial time-series technical indicators  
- Deep learning-based prediction model  

The `Original` folder contains baseline models and datasets, while the `Backtesting` and `Ablation` folders include validation, backtesting, and ablation experiments.

---

## Dataset Information

### 1. ESG News Data
- Source: LexisNexis  
- Keywords: "ESG", "esg"  
- Total Articles: 14,049  
- Period: Jan 1, 2016 – Jul 31, 2023  
- Purpose: ESG sentiment analysis  

> Due to licensing restrictions, raw news data cannot be publicly shared.

---

### 2. Stock Market Data
- Source: https://www.investing.com  
- Indices: S&P 500, DJIA  
- Features:
  - Open, High, Low, Close prices  
  - Trading volume  
  - Volatility  
- Frequency: Daily  

---

## Code Structure
```bash
├── Original/
│   ├── baseline models
│   └── datasets
│
├── Backtesting/
│   ├── backtesting scripts
│   ├── ablation studies
│   └── evaluation
└── 
---

## Methodology

The experimental pipeline follows:

1. Data Collection  
2. Data Preprocessing  
3. Feature Engineering  
   - ESG sentiment index  
   - Technical indicators  
4. Data Scaling  
5. Model Training (ATFN)  
6. Evaluation  
   - MAPE  
   - RMSE  
   - MAE  
   - R²  
7. Backtesting  
8. Ablation Study  

---
## Installation
You need to install four modules or library: numpy, scipy, pandas, os, tensorflow/keras, sklearn, matplotlib

## Contents
<img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=Python&logoColor=white"> ver 3.7.7

<img src="https://img.shields.io/badge/Keras-3776AB?style=plastic&logo=Keras&logoColor=white"> ver 2.5.0

<img src="https://img.shields.io/badge/Sklearn-3776AB?style=plastic&logo=Sklearn&logoColor=white"> ver 1.1.0


## Device
CPU: Intel(R) Core(TM) i7-10700F CPU @ 2.90GHz   2.90 GHz

RAM: 32.0GB

GPU: NVIDIA GeForce RTX 3070

## Usage Instructions

## Clone Repository
```bash
git clone https://github.com/your-repo/ATFN.git
cd ATFN


