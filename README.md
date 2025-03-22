# Medical-Insurance-Data-Analysis
This project aims to develop a predictive model for medical insurance costs using machine learning techniques, specifically linear regression. The model will leverage various features such as age, BMI, smoking habits, and geographical region to estimate insurance charges.<br>

Dataset: The project utilizes the "insurance.csv" dataset, which contains information about individuals' medical insurance details. The dataset includes features like age, sex, BMI, children, smoker status, region, and charges.<br>



1. Data Exploration and Preprocessing:<br> The dataset is loaded and explored using Pandas and visualized using Seaborn and Matplotlib. This stage involves handling missing values, removing duplicates, and identifying outliers using Z-score analysis.<br>

2. Feature Engineering:<br> One-hot encoding is applied to categorical features (sex, smoker, and region) to transform them into numerical representations suitable for modeling. Numerical features like age, BMI, children, and charges are standardized using StandardScaler to ensure consistent scaling.<br>

3. Model Training:<br> The data is split into training and testing sets. Linear regression is employed as the predictive model. The model learns the relationships between features and insurance charges based on the training data.<br>

4. Model Evaluation:<br> The trained model is evaluated on the testing data using metrics such as Mean Squared Error (MSE) and R-squared. These metrics assess the model's accuracy and goodness of fit.<br>

5. Prediction:<br>The model is then used to predict insurance charges for new data, leveraging the patterns learned from the training data.<br>

6. Model Persistence:<br> The trained model and scaler are saved using Pickle, allowing for future reuse without retraining. This enhances model usability and deployment.<br>

Feel free to download the data and code.
