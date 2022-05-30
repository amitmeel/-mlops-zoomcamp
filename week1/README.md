In week 1 of MLOps-zoomcamp we will learn about the below topics:
* what is MLOps
* How to create an EC2 instance (virtual server in cloud) on AWS
* How to connect to the EC2 instance from local machine with ssh
* How to install anaconda and use Python on EC2 instance
* How to install docker compose on EC2 instance and run hello-world
* How to connect Visual Studio Code terminal to EC2 instance with the help of Remote SSH extenstion from microsoft.
* How to start jupyter notebook on EC2 instance (Remote server/machine) and then run it on your local machine using port forwarding.
* How to read Parquet files using pandas.
* Train a machine learning model to predict the duration of ride (Dataset = [NYC Taxi dataset](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page))

**What is MlOps:**
----------------
MLOps stands for Machine Learning Operations. MLOps is a core function of Machine Learning engineering, focused on streamlining the process of taking machine learning models to production, and then maintaining and monitoring them.

There are various steps before we can deploy a model to production. for example, we need to:
1. data collection from various sources
2. data labelling
3. data validation (whether the data is valid for the rest of the process)
4. data preprocessing (EDA, data transformation and prepration)
5. model training
6. model evaluation
7. model deployment
8. model monitoring
9. model retraining based on feedback from users

So basically, MLOps is a set of practices for collaboration and communication between data scientists and operations professionals to simplify and automate the above mentioend steps and run AI projects successfully.


