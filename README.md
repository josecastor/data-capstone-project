# Data Engineering Capstone Project



## **Overview**
The objective of this Capstone project is to combine what they learned in Nanodegree. Capstone is will help the student achieve career goals related to data engineering. For this project we were given two options, to work with mass data regarding immigration from the United States or to define another scope together with the data.

## Discussion for the choice of tools and technologies for the project

We use technologies and resources available on AWS so that the services used are priced according to use, making it possible to start a small project the way it increases this can be scaled.

## Project Files

```create_redshift.py``` -> Code for create environment in AWS.

```create_tables.py``` -> Code for **fact** and **dimension tables** for the start schema in Redshift.

```dwh.cfg``` -> File for put your config of environment AWS.

```capstone_project.ipynb``` -> The ETL to reads data, processes that data using **Spark**, writes in **S3**, and copy to **Amazon Redshift**.

```README.MD``` -> Description about project for this ETL pipeline. 

```remove_redshift.py``` -> Code for remove environment in AWS.

```sql_queries.py``` -> Code sql queries for dropping, creating and insertion tables.


## How to run

Please, place your AWS **region**, **key** and **secret** in SECTION **AWS** into ```dwh.cfg```

Open file **capstone_project.ipynb** and click **Run All Cells** in menu **Run**

**Attention** - for destroy redshift on AWS, uncomment last cell in notebook jupyter and run this cell