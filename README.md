# 用户流失预测（Customer Churn Prediction）

> 基于 Telco 客户流失数据集，使用机器学习进行用户流失预测的完整实验。

## 📌 项目简介

根据客户的历史行为、合约类型、消费习惯等特征，预测客户是否会流失（Churn）。

项目包含完整的分析流程：数据清洗、探索性数据分析（EDA）、特征工程、模型训练与评估。所有内容均在 Jupyter Notebook 中完成。

📁 **核心文件**：[`x_user_churn_prediction.ipynb`](./x_user_churn_prediction.ipynb)

---

## 主要内容

- **数据理解与清洗**：处理缺失值、类型转换、冗余值合并
- **EDA 分析**：目标变量分布、类别特征与流失率的关系、数值特征分布、相关性分析
- **特征工程**：类别变量编码（LabelEncoder / OneHotEncoder）、特征缩放（MinMaxScaler）
- **模型训练**：使用多种分类器进行训练，包括逻辑回归、随机森林、XGBoost、CatBoost、LightGBM 等
- **模型评估**：准确率、召回率、F1-score、ROC-AUC 等多维度评估
- **可解释性分析**：使用 SHAP 进行模型解释

---

## requirements

- Python 3.x
- Pandas、NumPy
- Matplotlib、Seaborn
- Scikit-learn
- XGBoost、CatBoost、LightGBM
- SHAP

---

## 📊 数据集

使用公开数据集：**Telco Customer Churn Dataset**，包含约 7000 条客户记录，涵盖 20+ 个特征。

- 目标变量：`Churn`（Yes / No）
- 特征类型：数值型 + 类别型

---

## 项目结构
``` text
├── x_user_churn_prediction.ipynb # 完整实验 Notebook
├── README.md # 项目说明
└── WA_Fn-UseC_-Telco-Customer-Churn.csv # 数据集（需自行下载）

```

---

## 🔍 如何查看

由于 Notebook 包含完整的分析过程、可视化图表和代码注释，推荐直接打开查看：

👉 [点击查看完整 Notebook](./x_user_churn_prediction.ipynb)




本项目仅供学习参考使用。
