# Big_Mart_Sales_Prediction
 
## Overview

This repository contains a model for predicting item sales at Big Mart stores. It includes a trained machine learning model and a Streamlit application for user interaction.

## Prerequisites

Before using the model, ensure you have the following installed:

- Python 3.x
- Pip (Python package installer)
- Jupyter Notebook
- Aanaconda

## Installation

### Clone the Repository

First, clone this repository to your local machine:

Model and Preprocessor
Ensure you have the following files in your repository:

- model.pkl - The trained linear regression model.
- preprocessor.pkl - The preprocessor used for feature transformation.
These files should be placed in the root directory of your project.
### Running the Streamlit Application

1. **Save the Streamlit Code**

   - Save the `app.py` file from the repository in the root directory of your project.

2. **Start the Streamlit Application**

   - In your terminal, navigate to the directory containing `app.py`, and run:
     
     streamlit run app.py
     
This command will start a local server and open the Streamlit application in your default web browser.
### Using the Streamlit Application

1. **Open the Application**

   - Once the server is running, it will provide a URL (usually `http://localhost:8501`). Open this URL in your web browser.

2. **Input Your Data**

   - Fill out the form fields with the data you want to predict. 
   - You can select item identifiers, input numeric values, and choose categorical values from dropdowns.

3. **Get Predictions**

   - After filling in the required fields, the predicted sales value will be displayed on the page.

### Troubleshooting

- **File Not Found Error:** Ensure that `model.pkl` and `preprocessor.pkl` are in the same directory as your script.
- **Dependencies Issue:** Verify that all required packages are installed. Reinstall them if necessary.



### Contact

- For questions or comments, please open an issue on GitHub or contact jenish.maharjan07@gmail.com.
