Strava Project - Moving Time Prediction
This project utilizes exported data from Strava to analyze sports activities and apply Machine Learning models (such as K-Nearest Neighbors) to predict elapsed / moving time (moving_time) based on distance metrics, elevation, and physiological conditions.

📌 Project Links
Trello Board: ML - Trello
Project Presentation: Google Slides - Presentation
🚀 Project Workflow
Data Loading and Inspection:

Importing essential libraries (pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost).
Reading and parsing data exported from Strava (activities.csv).
Data Cleaning and Preparation:

Filtering exclusively for Run activities.
Handling and removing missing or incomplete values.
Standardizing data types, date formats (YYYYMMDD), and column names (translated to English).
Exporting the normalized dataset to strava_data_cleaned.csv.
Modeling and Evaluation (Machine Learning):

Splitting data into Training (Train) and Testing (Test) sets.
Model training using K-Nearest Neighbors (KNN Regressor) and other regression algorithms.
Evaluation of error metrics and accuracy.
Graphical visualization of predictions and data scatter plots.
🛠️ Requirements and Installation
Ensure you have Python 3.8+ installed and install the required packages by running:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost scipy
📊 How to Use
Place your activities.csv file (exported directly from Strava) in the root directory of the project.
Open the notebook in your preferred environment (Jupyter Notebook, JupyterLab, or VS Code).
Execute the cells sequentially to generate the cleaned dataset and visualize model performance.
