Real Estate Price Prediction Website
====================================

This data science project is focused on building a website that predicts real estate prices using a linear regression model built with scikit-learn. The dataset used for building the model is the Bangalore home prices dataset from Kaggle.com.

Project Components
------------------

1.  **Model Building**: We will use scikit-learn to build a linear regression model that will be used for real estate price prediction. During the model building process, we will cover various data science concepts, including data loading and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tuning, and k-fold cross-validation.

2.  **Python Flask Server**: We will build a Python Flask server that will use the saved model to serve HTTP requests.

3.  **Website**: The website will be built using HTML, CSS, and JavaScript. It will allow users to input information about the property, such as the square footage and number of bedrooms, and retrieve the predicted price from the Python Flask server.

Technologies and Tools Used
---------------------------

The following technologies and tools were used for this project:

-   Python
-   NumPy and Pandas for data cleaning
-   Matplotlib for data visualization
-   scikit-learn for model building
-   Jupyter Notebook, Visual Studio Code, and PyCharm as IDE
-   Python Flask for HTTP server
-   HTML/CSS/JavaScript for UI

How to Use the Project
----------------------

To use this project, follow these steps:

1.  Clone the repository to your local machine.
2.  Install the required dependencies using `pip install -r requirements.txt`.
3.  Run `python server.py` to start the Flask server.
4.  Open HTML file in you web browser to run the client.
5.  Input the required information about the property and click the "Predict Price" button.
6.  The predicted price for the property will be displayed on the website.
