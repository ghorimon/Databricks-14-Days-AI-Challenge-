# Databricks 14 Days AI Challenge 🚀

[![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)](https://databricks.com)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)](https://spark.apache.org)

A comprehensive 14-day journey through Databricks, covering data engineering, machine learning, and AI capabilities on the Databricks Data Intelligence Platform.

## 📚 Table of Contents

- [Overview](#overview)
- [Challenge Structure](#challenge-structure)
- [Prerequisites](#prerequisites)
- [Setup Instructions](#setup-instructions)
- [Daily Challenges](#daily-challenges)
- [Project Structure](#project-structure)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This repository contains solutions and learning materials for the **Databricks 14 Days AI Challenge** organized by the Indian Data Club. The challenge is designed to help you master Databricks fundamentals, advanced data engineering concepts, machine learning workflows, and generative AI applications.

## 🗓️ Challenge Structure

### Week 1: Foundations & Data Engineering
- **Day 1-2**: Databricks Fundamentals & Workspace Navigation
- **Day 3-4**: Delta Lake & Data Ingestion
- **Day 5-7**: Advanced PySpark & ETL Pipelines

### Week 2: Machine Learning & AI
- **Day 8-9**: MLflow & Model Training
- **Day 10-11**: Feature Engineering & AutoML
- **Day 12-13**: Generative AI with Mosaic AI
- **Day 14**: Capstone Project & Deployment

## 🔧 Prerequisites

- Databricks Community Edition account or Databricks Trial
- Basic Python programming knowledge
- Understanding of SQL fundamentals
- Familiarity with data concepts (optional but helpful)

## 🚀 Setup Instructions

### 1. Databricks Account Setup

```bash
# Sign up for Databricks Community Edition
# Visit: https://community.cloud.databricks.com/

# Or get a trial account
# Visit: https://databricks.com/try-databricks
```

### 2. Clone This Repository

```bash
git clone https://github.com/yourusername/databricks-14days-challenge.git
cd databricks-14days-challenge
```

### 3. Import Notebooks to Databricks

1. Navigate to your Databricks workspace
2. Click on **Workspace** → **Users** → **Your Username**
3. Click **Import** → **URL** or **File**
4. Import the notebooks from the `notebooks/` directory

### 4. Install Required Libraries

Create a cluster and install the following libraries:
```python
# Requirements are specified in requirements.txt
pandas
numpy
matplotlib
seaborn
mlflow
scikit-learn
```

## 📖 Daily Challenges

### Day 1: Introduction to Databricks
**Topics**: Workspace navigation, notebooks, clusters
- [ ] Create your first notebook
- [ ] Understand workspace structure
- [ ] Create and configure a cluster

📁 **Notebook**: `notebooks/day01_databricks_intro.ipynb`

### Day 2: Databricks File System (DBFS)
**Topics**: DBFS, data storage, file operations
- [ ] Explore DBFS structure
- [ ] Upload and manage datasets
- [ ] Practice file operations

📁 **Notebook**: `notebooks/day02_dbfs_operations.ipynb`

### Day 3: Introduction to Delta Lake
**Topics**: Delta tables, ACID transactions, time travel
- [ ] Create Delta tables
- [ ] Perform CRUD operations
- [ ] Use time travel features

📁 **Notebook**: `notebooks/day03_delta_lake_basics.ipynb`

### Day 4: Data Ingestion Patterns
**Topics**: Batch and streaming ingestion, Auto Loader
- [ ] Implement batch data loading
- [ ] Set up streaming pipelines
- [ ] Use Auto Loader for cloud storage

📁 **Notebook**: `notebooks/day04_data_ingestion.ipynb`

### Day 5: PySpark Fundamentals
**Topics**: DataFrames, transformations, actions
- [ ] Master DataFrame operations
- [ ] Apply transformations
- [ ] Understand lazy evaluation

📁 **Notebook**: `notebooks/day05_pyspark_basics.ipynb`

### Day 6: Advanced PySpark
**Topics**: Window functions, UDFs, optimization
- [ ] Use window functions
- [ ] Create custom UDFs
- [ ] Optimize Spark jobs

📁 **Notebook**: `notebooks/day06_advanced_pyspark.ipynb`

### Day 7: Building ETL Pipelines
**Topics**: Delta Live Tables, pipeline orchestration
- [ ] Design ETL workflows
- [ ] Implement Delta Live Tables
- [ ] Schedule and monitor pipelines

📁 **Notebook**: `notebooks/day07_etl_pipelines.ipynb`

### Day 8: Machine Learning Basics
**Topics**: ML workflows, feature engineering
- [ ] Prepare data for ML
- [ ] Split train/test datasets
- [ ] Create feature pipelines

📁 **Notebook**: `notebooks/day08_ml_basics.ipynb`

### Day 9: MLflow Integration
**Topics**: Experiment tracking, model registry
- [ ] Track experiments with MLflow
- [ ] Log parameters and metrics
- [ ] Register models

📁 **Notebook**: `notebooks/day09_mlflow_tracking.ipynb`

### Day 10: AutoML
**Topics**: Automated machine learning, model selection
- [ ] Use Databricks AutoML
- [ ] Compare model performance
- [ ] Deploy best models

📁 **Notebook**: `notebooks/day10_automl.ipynb`

### Day 11: Feature Store
**Topics**: Feature engineering, feature store, reusability
- [ ] Create feature tables
- [ ] Use Feature Store for training
- [ ] Ensure feature consistency

📁 **Notebook**: `notebooks/day11_feature_store.ipynb`

### Day 12: Generative AI Foundations
**Topics**: LLMs, embeddings, vector databases
- [ ] Understand LLM concepts
- [ ] Generate embeddings
- [ ] Work with Vector Search

📁 **Notebook**: `notebooks/day12_genai_foundations.ipynb`

### Day 13: RAG Applications
**Topics**: Retrieval-Augmented Generation, Mosaic AI
- [ ] Build RAG pipelines
- [ ] Use Mosaic AI Playground
- [ ] Create AI applications

📁 **Notebook**: `notebooks/day13_rag_applications.ipynb`

### Day 14: Capstone Project
**Topics**: End-to-end data & AI project
- [ ] Design complete solution
- [ ] Implement data pipeline
- [ ] Deploy ML/AI model
- [ ] Create dashboard/visualization

📁 **Notebook**: `notebooks/day14_capstone_project.ipynb`

## 📁 Project Structure

```
databricks-14days-challenge/
│
├── notebooks/                      # Daily challenge notebooks
│   ├── day01_databricks_intro.ipynb
│   ├── day02_dbfs_operations.ipynb
│   ├── day03_delta_lake_basics.ipynb
│   ├── day04_data_ingestion.ipynb
│   ├── day05_pyspark_basics.ipynb
│   ├── day06_advanced_pyspark.ipynb
│   ├── day07_etl_pipelines.ipynb
│   ├── day08_ml_basics.ipynb
│   ├── day09_mlflow_tracking.ipynb
│   ├── day10_automl.ipynb
│   ├── day11_feature_store.ipynb
│   ├── day12_genai_foundations.ipynb
│   ├── day13_rag_applications.ipynb
│   └── day14_capstone_project.ipynb
│
├── data/                           # Sample datasets
│   ├── sample_data.csv
│   ├── sales_data.json
│   └── README.md
│
├── src/                            # Python modules and utilities
│   ├── __init__.py
│   ├── data_processing.py
│   ├── feature_engineering.py
│   └── utils.py
│
├── config/                         # Configuration files
│   ├── cluster_config.json
│   └── pipeline_config.yaml
│
├── docs/                           # Documentation
│   ├── setup_guide.md
│   ├── best_practices.md
│   └── troubleshooting.md
│
├── tests/                          # Unit tests
│   ├── test_data_processing.py
│   └── test_feature_engineering.py
│
├── .gitignore
├── requirements.txt
├── LICENSE
└── README.md
```

## 📚 Resources

### Official Databricks Documentation
- [Databricks Documentation](https://docs.databricks.com/)
- [Delta Lake Guide](https://docs.delta.io/)
- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)
- [PySpark API Reference](https://spark.apache.org/docs/latest/api/python/)

### Learning Materials
- [Databricks Academy](https://www.databricks.com/learn/training)
- [Databricks Community Edition](https://community.cloud.databricks.com/)
- [Apache Spark Documentation](https://spark.apache.org/docs/latest/)

### Community
- [Indian Data Club](https://indiandataclub.com)
- [Databricks Community Forums](https://community.databricks.com/)
- [Stack Overflow - Databricks Tag](https://stackoverflow.com/questions/tagged/databricks)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Indian Data Club** for organizing this challenge
- **Databricks** for providing the platform and resources
- All contributors and participants in this learning journey

## 📧 Contact

For questions or feedback:
- Create an issue in this repository
- Join the Indian Data Club community
- Connect on LinkedIn

---

**Happy Learning! 🎉**

*Start your Databricks journey today and become a Data & AI expert!*
