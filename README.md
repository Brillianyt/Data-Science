# 🚀 Data Science Roadmap & Lab

<p align="left">
  <img src="https://img.shields.io/badge/Status-Learning-orange.svg" alt="Status">
  <img src="https://img.shields.io/badge/Tech-SQL%20%7C%20Hive%20%7C%20ML-blue.svg" alt="Tech">
  <img src="https://img.shields.io/badge/Tools-Scikit--learn%20%7C%20Pandas-red.svg" alt="ML-Tools">
</p>

> **“数据科学是发现真相的艺术。”** > 这个仓库记录了我从 0 到 1 沉淀的核心能力，重点涵盖了 **端到端的机器学习建模流程**、大数据集群处理及商业分析实战。

---

## 🤖 机器学习核心实验室 (ML Priority)
*本仓库的核心重点，强调工业级的建模闭环：*

### 🔄 建模全生命周期 (End-to-End Workflow)
1. **[数据探索 EDA]**: 缺失值分析、特征相关性热力图、偏态分布处理。
2. **[特征工程]**: 
   - 编码：One-Hot, Label Encoding, Target Encoding。
   - 降维：PCA 主成分分析、特征重要性筛选 (Feature Selection)。
   - 转换：PowerTransform, StandardScaler。
3. **[模型选型]**: 从线性模型 (Logistic Regression) 到集成学习 (XGBoost, LightGBM)。
4. **[评估优化]**: 交叉验证 (Cross-Validation)、GridSearch 超参数调优、ROC/AUC/F1-Score 多指标评估。

### 🧪 算法实战记录
- [ ] **分类任务**: 电信客户流失预测 (Binary Classification)
- [ ] **回归任务**: 房价预测与 L1/L2 正则化对比
- [ ] **聚类任务**: 基于 RFM 模型的海量用户分层 (K-Means)

---

## 🧭 知识航线 (Knowledge Map)

### 💎 1. SQL 精炼厂 (The SQL Refinery)
* **[进阶]** **窗口函数 (Window Functions)**、CTE、复杂分桶、用户留存/漏斗分析逻辑。

### 📦 2. 大数据集群工具 (Hive & Clusters)
* **ETL 流程**: 原始数据 (ODS) → 仓库层 (DW) → 应用层 (ADS) 的构建与数据倾斜优化。

### 📊 3. Tableau 可视化看板 (BI Insights)
* **方法论**: 维度与度量的组合、动态筛选器设计、故事线 (Storytelling) 搭建。

---

## 🛠 技能栈可视化 (Toolbox)

| 领域 | 技术栈 | 熟练度 |
| :--- | :--- | :--- |
| **机器学习** | Scikit-learn, XGBoost, CatBoost | ███████░░░ |
| **数据处理** | Pandas, Numpy, HiveQL | ██████░░░░ |
| **可视化** | Tableau, Matplotlib, Seaborn | ██████░░░░ |
| **大数据** | Hadoop, Hive, Spark (Learning) | ████░░░░░░ |

---

## 📂 仓库结构 (File Structure)

```bash
Data-Science/
├── 01_ML_Lab/            # 🚀 重点：Jupyter Notebooks 建模全过程
│   ├── EDA_Reports/      # 数据分析报告
│   └── Models/           # 训练脚本与模型持久化
├── 02_SQL_Bank/          # SQL 经典题库与解析
├── 03_Hive_Cluster/      # Hive 配置与大数据 ETL
└── 04_Tableau_Gallery/   # 商业看板截图


📬 交流与联系
My GitHub: Brillianyt

目标: 持续输出，迈向 Senior Data Scientist。