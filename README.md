# ProfitHarvest-Crop-Recommendation-for-Sustainable-Farmer-Income-Growth-
<h3>workflow of the project</h3>
recommendation of best 3 crops for the specific land by doing the soil test analysis and predicting their prices of that crops which results to take better decisions for the farmers to cultivate the crop in their land and get better yields
<br>
<h3>files</h3>
In the templates folder, there are two files named index.html and result.html, along with a separate file named app.py.
<br>
<h3>models</h3>
For the crop recommendation, we used a machine learning model called the Stacking Classifier. It is an ensemble model comprising four base classifiers: Decision Tree (DT), Naive Bayes (NB), Support Vector Machine (SVM), and K-Nearest Neighbors (KNN). Additionally, SVM was used as the meta-model for the final recommendation.
<br>
For the price prediction, we used a deep learning model called the Long Short-Term Memory (LSTM) model, which is highly effective for time series forecast.
<br>
<h3>datasets</h3>
For the crop recommendation model, we used a soil analysis dataset containing eight features: Nitrogen, Phosphorus, Potassium, Rainfall, pH, Humidity, Temperature, and Crop.
<br>
For the price prediction model, we used historical crop price data, which provided insights into market trends and helped analyze the price patterns of crops.
we have used "www.commodityonline.com" for collecting the price dataset.
