# KNN5-CropPredictor
<h2>Project Overview<br></h2>
<h3>Project Title :</h3>
<h4> KNN5-CropPredictor</h4>
<h3>Project Description : </h3>
<h4>Crop recommendation system using machine learning to optimize crop selection based on soil, climate, and other relevant factors.</h4>
<h3>Problem Statement: </h3>
<h4>Suboptimal crop selection based on soil and climatic conditions leads to reduced crop yields and economic losses for farmers.</h4>
<h3>Solution : </h3>
<h4>A crop recommendation system aims to optimize agricultural productivity by suggesting suitable crop varieties based on specific soil and climatic conditions.</h4>
<h2>Dataset:</h2>
<h3>Data Source: Dataset for this project was sourced from Kaggle .</h3>
<h3>Data Preprocessing: we need to clean our data by handling missing values and inconsistencies.</h3> 
<h3>Data Features: </h3>
<h4>Soil Properties:</h4>
<p>N - ratio of Nitrogen content in soil<br>
P - ratio of Phosphorous content in soil<br>
K - ratio of Potassium content in soil<br>
ph - ph value of the soil</p>
<h4>Environmental factors:</h4>
<p>temperature - temperature in degree Celsius<br>
humidity - relative humidity in %<br>
rainfall - rainfall in mm</p>
<h2>Model Architecture</h2>
<h3>Model Type: KNN (K-Nearest Neighbors).It is based on similarity to nearest data points.</h3>
<h3>Model Parameters: </h3><h4>I have specified the number of neighbors (k) as a parameter. I have experimented with different k values and found that k=5 is the optimal one for my data.</h4>
<h3>Training and Evaluation: </h3><h4>Split the data into training and testing sets using train_test_split. The training set will be used to train the KNN model, and the testing set will be used to evaluate its performance on unseen data.</h4>
<h2>Usage Instructions</h2>
<h3>Installation: I have used google colab platform</h3>
<h3>Setting Up Your Project in Google Colab </h3>
<h4>1. Create a New Colab Notebook<br>
Go to <a href="https://colab.research.google.com/">https://colab.research.google.com/</a><br>
Click on "New notebook"<br>
2. Add dependencies<br>
3. Upload Your Dataset<br>
Click on the folder icon on the left sidebar<br>.
Upload your dataset (in CSV or Excel format) to the Colab environment.<br>
4. Load the Dataset<br>
5. Explore and Preprocess Data<br>
Use pandas functions to explore the dataset<br>
By following these steps, you'll have a basic setup project in Google Colab. You can then proceed with data splitting, model building, training, and evaluation. 
</h4>
<h3>Data Preparation: </h3>
<h4>You can get this data from <a href="https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset">https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset</a></h4>
<h3>Model Performance: </h3>
<h4>Accuracy on training data: 0.9795454545454545<br>
Accuracy on test data: 0.9676136363636364
</h4>
<h2>Potential Enhancements: </h2>
<h4>Develop a Web Interface: Create a user-friendly web interface where users can easily input their land characteristics and receive crop recommendations. This could involve frameworks like Flask or Django.<br>
Mobile App Integration: Develop a mobile app that allows users to take pictures of their land or input data on-site to receive crop recommendations.<br>
API Integration: If your model is part of a larger agricultural system, consider developing an API that allows other applications to interact with your model and retrieve crop recommendations.</h4>
