# SparkSQL Task

This repository contains a SparkSQL task for analyzing home sales data using Apache Spark and Hadoop on a Windows environment.

## Prerequisites

Before running the code, ensure you have the following installed:

- Python 3.8+
- Apache Spark 3.0+
- Hadoop 3.4.0 (configured for Windows)

## Setup Instructions

1. **Install Spark and Hadoop:**
   - Download and install [Apache Spark](https://spark.apache.org/downloads.html).
   - Download and install [Hadoop](https://hadoop.apache.org/releases.html).

2. **Set Environment Variables:**
   - Add Hadoop to your environment variables:
     ```bash
     set HADOOP_HOME=C:\path\to\hadoop-3.4.0
     set PATH=%PATH%;%HADOOP_HOME%\bin
     ```

3. **Install Python Dependencies:**
   ```bash
   pip install findspark pyspark

## Running the Code

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/sparksql-task.git
    cd sparksql-task
    ```

2. **Download the Data:**
The data is automatically downloaded from an AWS S3 bucket.

3. **Run the Jupyter Notebook:**
Start Jupyter Notebook and run the provided notebook to execute the tasks.
    ```bash
    jupyter notebook
    ```

### Conclusion
This project demonstrates how to set up and run SparkSQL tasks in a Windows environment using Apache Spark and Hadoop. It covers reading data from an AWS S3 bucket, performing SQL queries, and working with Parquet files.
For more details, refer to the provided Jupyter Notebook.
