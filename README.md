# Capital Cost Prediction for RO Desalination Plants Using Machine Learning

Project Overview
This project aims to predict the capital cost of Reverse Osmosis (RO) based desalination plants using machine learning. The dataset used consists of 1806 RO plants with a capacity of at least 1000 m³/day, incorporating six input features:

Plant Location
Plant Capacity
Project Award Year
Raw Water Salinity
Plant Types
Project Financing Type
The output is the capital cost of the desalination plant.

Approach
The project uses a multi-layer feedforward neural network with a backpropagation learning method for model training and prediction. The model is designed to predict the capital cost based on the provided input features.

Dataset
The dataset includes detailed information about the plants, including location, size, and salinity factors, which directly influence the cost of construction and operation.

Technologies Used
Machine Learning Framework: PyTorch
Programming Language: Python
Libraries: NumPy, Pandas, Matplotlib
Model Description
The model will be trained using regression techniques to make accurate predictions on the capital cost of RO desalination plants based on the input features. The results of the trained model will be deployed through a web interface, allowing users to input plant data and obtain capital cost predictions.
