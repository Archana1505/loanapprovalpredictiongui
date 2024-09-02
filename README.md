# loanapprovalpredictiongui
loan approval prediction involves designing an interface where users can input relevant data, submit it, and receive a prediction regarding the approval of their loan.
Features and Functionality:
Data Loading:

The logistic regression model is loaded using pickle.
An Excel file containing relevant data (loan.xlsx) is read using pandas. This data is used to populate dropdowns with unique values for each category.
GUI Components:

Image and Title: The background image and the title “Loan Approval Prediction” are displayed at the top.
Input Fields: Various input fields are provided for:
Gender
Marital Status
Number of Dependents
Education Level
Loan Amount Term
Credit History
Log Amount
Total Income
Prediction Button: A "PREDICT" button triggers the model to predict whether the loan will be approved or not.
Result Display: A label to display the prediction result ("YES" or "NO").
Prediction Functionality:

The predict_output function gathers input data from the user, converts it into a DataFrame, and uses the logistic regression model to make a prediction. The result is displayed on the GUI.
