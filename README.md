# Task1---Big-Data-Analysis
# Big Data Analysis with PySpark on Google Colab

## 📌 Objective
Perform scalable data analysis on a large dataset using **Apache PySpark** in a cloud-based notebook environment (Google Colab), with no local installation required.

---

## ⚙️ Tools Used
- **Google Colab**: Free online Jupyter notebook platform
- **Apache PySpark**: Big data processing framework
- **Python**: Programming language for data analysis
- **Public CSV Dataset**: Large dataset used to demonstrate Spark's scalability

---

## 🚀 How to Run the Notebook

1. **Open Google Colab**  
   Go to [https://colab.research.google.com](https://colab.research.google.com)

2. **Install Dependencies**  
   Run the following in the first code cell to install Java and PySpark:
   ```python
   !apt-get install openjdk-8-jdk-headless -qq > /dev/null
   !pip install -q pyspark
   import os
   os.environ["JAVA_HOME"] = "/usr/lib/jvm/java-8-openjdk-amd64"
