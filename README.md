
# ETL PipeLine

This project is an ETL pipeline that extracts data from a source, performs transformations on the data, and loads it into a target destination. The purpose of this project is to automate the process of data extraction, transformation, and loading, and to provide a scalable and maintainable solution for handling large volumes of data.

## Getting Started
To get started with this project, you will need to clone the repository to your local machine and install any required dependencies. You can do this by running the following commands:


## 

#### bash

```http
  git clone https://github.com/your-username/etl-pipeline-project.git
cd etl-pipeline-project
pip install -r requirements.txt

```
Once you have installed the required dependencies, you can run the ETL pipeline by running the following command:
```http
  python etl_pipeline.py


```
## Project Sructure

The project consists of the following files:

etl_pipeline.py: The main script that runs the ETL pipeline.

config.py: Configuration file that contains database connection details and other settings.

utils.py: Utility functions used by the ETL pipeline.

data/: Directory containing the source data files.

sql/: Directory containing SQL scripts used by the ETL pipeline.

requirements.txt: File containing a list of required dependencies



## How the ETL Pipeline Works

The ETL pipeline works in the following way:

1.Extract: The pipeline reads data from one or more source files and loads it into memory as a pandas DataFrame.

2.Transform: The pipeline performs various transformations on the data, such as cleaning, filtering, and aggregating. 
These transformations are defined in the utils.py file.

3.Load: The pipeline loads the transformed data into a target database table using SQL scripts defined in the sql/ directory.


## Authors

- [@hemanth-kumar](https://www.github.com/hemanth-kumar-boddeda)

