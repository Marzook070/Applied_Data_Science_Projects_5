Dependencies required:
pandas	pip install pandas
numpy	pip install numpy

.ipynb can be run in the jupyter notebook
.py can be run in the terminal

Description:
Design Thinking:

Data Source Selection: Our primary data source is a comprehensive dataset containing information about various movies. This dataset includes crucial attributes such as genre, premiere date, runtime, language, and IMDb scores. IMDb scores, as the target variable, are of particular significance as they represent the movie's overall reception and popularity among viewers.

Data Preprocessing: Data preprocessing is a pivotal step to ensure the quality and reliability of our dataset. It involves techniques such as data cleaning, handling missing values, and transforming categorical features into numerical representations. This ensures that our data is suitable for machine learning algorithms, which typically require numerical input.

Feature Engineering: Feature engineering is the process of selecting, creating, or transforming features in the dataset to enhance the model's predictive capability. In our case, we'll explore various aspects of the movie dataset to identify and extract relevant features that can influence IMDb scores. This may include creating new features or transforming existing ones to capture valuable information.

Model Selection: Choosing the right regression algorithm is a crucial decision in our project. Regression algorithms like Linear Regression and Random Forest Regressor are potential candidates for predicting IMDb scores. The selection will depend on the dataset's characteristics and the model's performance.

Model Training: Once the appropriate regression algorithm is selected, we'll proceed to train the model using the preprocessed dataset. This step involves feeding the model with historical data (features) and IMDb scores (target variable) to allow it to learn the relationships between these variables.

Evaluation: To assess the model's performance, we will employ common regression metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²). MAE measures the average prediction error, MSE quantifies the squared errors, and R² gauges how well the model explains the variance in IMDb scores.
