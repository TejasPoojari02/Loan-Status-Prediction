# Loan Status Prediction Website

## Overview

This project is a machine learning-based Loan Status Prediction Website. Users can predict whether their loan application will be approved or not by entering various details such as applicant income, co-applicant income, loan amount, dependents, loan amount term, credit history, gender, marital status, employment status, graduation status, and property area. The website is visually appealing and user-friendly.

## Features

- **User Input Form**: Collects details required for loan status prediction.
- **Prediction Model**: Machine learning model to predict loan approval status.
- **Results Display**: Shows the prediction result in a clear and understandable manner.
- **Visual Appeal**: Modern and responsive design for an enhanced user experience.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/TejasPoojari02/Loan-Status-Prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd loan-status-prediction
    ```
3. Set up a Python virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Application**:
    ```bash
    python app.py
    ```
2. Open your web browser and go to `http://localhost:5000`.

3. **Fill in the Loan Application Form**:
    - Enter the following details:
        - Applicant Income
        - Co-applicant Income
        - Loan Amount
        - Number of Dependents
        - Loan Amount Term
        - Credit History
        - Gender
        - Marital Status
        - Employment Status
        - Graduation Status
        - Property Area

4. **Submit the Form**: Click the submit button to get the prediction result.

5. **View the Result**: The website will display whether your loan is likely to be approved or not.


## Machine Learning Model

- The machine learning model is trained on a dataset containing historical loan application data.
- The model uses features such as applicant income, co-applicant income, loan amount, dependents, loan amount term, credit history, gender, marital status, employment status, graduation status, and property area to predict loan approval.
- The model is saved as `loan_model.pkl` and loaded in `app.py` for making predictions.

## Contributing

If you would like to contribute to this project, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

If you have any questions or suggestions, feel free to contact me at tejaspoojari02@gmail.com).

---

**Note:** This is a basic implementation intended for demonstration purposes. For a production-level application, additional features and security measures should be implemented.

---

Enjoy predicting your loan approval status!
