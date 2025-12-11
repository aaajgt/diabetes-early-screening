# 糖尿病早期筛查机器学习模型

## 项目简介
本项目基于机器学习算法构建糖尿病早期筛查模型，对比了逻辑回归、随机森林经的性能，旨在为临床糖尿病早期筛查提供高精度、易部署的工具。项目包含完整的数据预处理流程、模型训练/调参/评估代码，以及可视化分析结果，可直接复现所有实验结论。

### 核心内容
- 数据清洗与特征工程；
- 逻辑回归/随机森林模型的训练、超参数调优；
- 模型性能评估（混淆矩阵、ROC-AUC、PR曲线、特征重要性分析）；
- 不同模型的性能对比与场景适配性分析。

## 数据说明
### 数据来源
- 原始数据链接：采用[Early Stage Diabetes Risk Prediction Dataset](https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset)

## 运行环境
### 基础环境
- Python版本：3.8

### 依赖包
```txt
numpy
pandas
scikit-learn
matplotlib
seaborn
