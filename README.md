Solar Power Prediction Project(Predicting solar panel power output using environmental data)

Domain: AIML
Topic: Sustainable Energy & Efficiency
Week: 1
About This Project
Photonix is a project focused on predicting solar panel power output (Watts) based on environmental conditions and panel settings. The project aims to help understand factors affecting solar energy efficiency and prepare the dataset for future machine learning models.
This Week 1 submission covers data preparation: creating a dataset, exploring it, preprocessing, and splitting it into training and testing sets.
Features & Target
Feature	Description
Sunlight_Hours 🌞	Hours of sunlight received
Temperature 🌡️	Ambient temperature in °C
Cloud_Cover ☁️	Percentage of sky covered by clouds
Panel_Angle 📐	Angle of the solar panel
Humidity 💧	Atmospheric humidity percentage
Wind_Speed 🍃	Wind speed in km/h
Target ⚡	Power_Output_Watts – solar panel power output
Week 1 Tasks Completed
Defined the problem statement and listed features/target.
Created a synthetic solar power dataset.
Explored the dataset with summary statistics and info.
Checked for missing values and confirmed data cleanliness.
Split the dataset into training (80%) and testing (20%) sets for ML readiness.
Dataset
File: photonix_dataset.csv
Contains 10 rows and 7 columns (6 features + 1 target).
Matches the dataset used in the Python code for Week 1.
How to Run
1. Clone the repository:
git clone https://github.com/kowshalyagp/Solar-power-prediction-using-machine-learning
2. Install dependencies:
pip install pandas scikit-learn
3. Run the Python script or Colab notebook:
python solar power prediction using machine learning_week1.py
4. The script will:
Display sample dataset
Show dataset info and summary statistics
Check for missing values
Split data into train and test sets
Save the dataset as solar power prediction using machine learning_dataset.csv
Future Work
Add machine learning models to predict solar panel output.
Perform model evaluation and optimization.
Visualize feature effects on power output for better insights.
