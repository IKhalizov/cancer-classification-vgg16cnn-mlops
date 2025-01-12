### MLOPs cancer classification project, using python data pipelines, with tensorflow, keras, data version control, MLFlow.  

The goal of this project is to understand how to build full cycle of machine learning model training. In the project was used tensorflow keras vgg16 CNN model as base model and it was trained with Chest CT-Scan images Dataset from Kaggle, with freeze layers technique.  

# Pipelines stages are:

1. Data ingestion
2. Model preparation
3. Model training
4. Model evaluation

Precision of the trained model was not the goal, but we can adjust it trough pipeline stages with epochs parameter and other hyper parameters. Right now recision of the model is 0.96 with 100 epochs.  

The project can be run locally, with Dockerfile, which is in the root of the project. You can easily modify urls and other configurations in the project for your data. 

The next step of this project is to deploy it on AWS cloud.
