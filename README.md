# Spark UI Simulator Study Notes

This repository contains my personal study notes, experiment logs, and insights gathered while learning Apache Spark using the [Spark UI Simulator](https://www.databricks.training/spark-ui-simulator/index.html) provided by **Databricks**.

> ⚠️ **Disclaimer**: I am not the creator or maintainer of the Spark UI Simulator. This project is an independent learning effort and is not affiliated with Databricks.

---

## 📚 About the Spark UI Simulator

The [Spark UI Simulator](https://www.databricks.training/spark-ui-simulator/index.html) is a free, interactive tool by Databricks that mimics the real Spark web UI. It provides:
- Preloaded simulated Spark jobs and stages
- Visual access to Jobs, Stages, Tasks, Executors, and SQL tabs
- A safe environment to practice Spark UI analysis **without needing a live cluster**

It’s widely used in Databricks training courses like **Optimizing Apache Spark on Databricks**.

---

## 🎯 Why This Repository Exists

I'm using this space to:
- Practice interpreting the Spark UI
- Document metrics related to job execution, partitioning, task skew, executor usage, etc.
- Deepen my understanding of how Spark works under the hood
- Build a reference I can revisit or share with others learning Spark performance tuning

---

## 🔍 What You’ll Find Here

Each experiment typically includes:
- A description of the simulated job
- Observations on job and stage performance
- Insights into shuffle behavior, task skew, and partition sizes
- Screenshots from the Spark UI Simulator
- Reflections on how performance could be optimized

---

## 🧠 Learning Goals

- Understand how Spark distributes workloads across cores and executors
- Detect common performance bottlenecks (e.g., skew, shuffles, spill, GC pauses)
- Learn how configuration parameters (like `spark.sql.shuffle.partitions` or `spark.sql.files.maxPartitionBytes`) affect execution
- Build confidence reading real Spark UI metrics

---

## 📎 Helpful Links

- 🔗 [Spark UI Simulator (Databricks)](https://www.databricks.training/spark-ui-simulator/index.html)
- 📘 [Official Spark UI Guide – Databricks Docs](https://docs.databricks.com/en/optimizations/spark-ui-guide.html)
- 💡 [Understanding performance on Databricks using Spark UI – Nubank Blog (PT-BR)](https://building.nubank.com.br/pt-br/entendendo-performance-no-databricks-usando-o-spark-ui/)

---

## 🙋‍♂️ Who Am I?

I'm a data enthusiast using this repository as a sandbox to better understand Apache Spark performance concepts. This repo is public in case it helps others on the same journey.

---

## 📬 Feedback

Have suggestions, questions, or want to share resources? Feel free to open an issue or discussion. Let's learn together.


