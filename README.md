# Weather-Predictor-using-decision-trees
A Python-based weather predictor that uses Decision Trees to classify rainfall based on environmental data.

Dataset Features
The model analyzes the following features from the weather_forecast_data.csv:
Temperature: The heat level in Celsius.
Humidity: The moisture level in the air.
Cloud Cover: Percentage of the sky covered by clouds.
Wind Speed & Pressure: Additional environmental factors.

Model Logic & Results
The model was trained using Scikit-Learn with a max_depth of 3 to ensure the decision logic remains readable.

1. Decision Tree Visualization
This diagram shows the "questions" the model asks to reach a conclusion.

3. Confusion Matrix
This matrix evaluates the accuracy of our predictions on the test set.

3. Performance
Accuracy: 100% (The model perfectly classified the provided sample dataset).
Key Predictors: Cloud Cover and Temperature were found to be the most significant factors in this dataset.

Conclusion
This project successfully visualizes the decision-making process of a supervised learning algorithm. 
It demonstrates that even with a simple tree structure, high accuracy can be achieved on well-structured environmental data.
