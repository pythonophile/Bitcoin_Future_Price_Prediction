# Bitcoin_Future_Price_Prediction
The code loads a pre-trained LSTM model to  predict Bitcoin prices. It fetches historical Bitcoin price data using  the yFinance library. The data is normalized and split into training  and testing sets. The LSTM model is used to predict future prices based  on the test data. Predictions and actual prices are visualized in  Streamlit.

To create the GitHub repository requirement file (commonly named requirements.txt), you need to include all the necessary Python libraries along with their versions that are required for the project. Based on the provided project details, here's the content for your requirements.txt:

numpy==1.24.3

pandas==2.0.3

matplotlib==3.7.1

yfinance==0.2.26

scikit-learn==1.3.0

streamlit==1.25.0

tensorflow==2.12.0

keras==2.12.0

Steps to create the requirements.txt file:

Open your project folder.

Create a new text file and name it requirements.txt.

Copy and paste the content above into the file.

Save the file.

This file will allow anyone cloning your GitHub repository to install the necessary packages by running:

bash
Copy code
pip install -r requirements.txt
Make sure to test the requirements.txt file to ensure it works correctly in a fresh environment.
