Python and Libraries: First, ensure Python is installed on your computer.
You'll need the pandas library for handling datasets, sklearn (scikit-learn) for machine learning models and metrics, and xlsxwriter for creating Excel files.

Python Installation: Ensure Python is installed on your system.
Pandas Package: Install pandas for data manipulation and analysis.
Sklearn Package: Install scikit-learn for machine learning algorithms.
XlsxWriter Package: Install XlsxWriter for writing files to Excel format.
Data Files: Ensure 'EdgeHistogram.csv' and 'Images.csv' are available and paths are correctly set in the code.

Installation Commands: Use pip, Python's package installer, to install necessary libraries if you haven't already:

pip install pandas
pip install scikit-learn
pip install XlsxWriter

Data Preparation: The program requires two CSV files: EdgeHistogram.csv and Images.csv. These should be correctly formatted and placed in an accessible location. The paths to these files must be specified in the code.

Functionality Overview: This script merges features from the EdgeHistogram.csv with labels from Images.csv, splits the data for training and testing, trains KNN, Decision Tree, and Random Forest classifiers, generates confusion matrices for each classifier, and saves the hyperparameters used in CSV format.

Output: Expect Excel files with confusion matrices and CSV files documenting the hyperparameters for each model, showcasing the use of classification techniques in machine learning.




