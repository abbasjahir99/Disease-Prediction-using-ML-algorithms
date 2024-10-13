# Disease Prediction Using Machine Learning

## Project Overview
This project is designed to predict diseases such as Heart Disease, Lung Cancer (COPD), and Diabetes using machine learning algorithms. It utilizes datasets from the UCI repository and applies supervised learning techniques like Decision Trees and Random Forest classifiers to help in early diagnosis.

### Abstract
Machine learning is rapidly becoming a critical tool in medical diagnostics. This project demonstrates how disease classification systems can provide early detection and prognosis of fatal diseases. Using three different datasets, features were selected with backward modeling and p-value tests. The models predict diseases like heart disease, lung cancer, and diabetes, providing a useful diagnostic tool for medical professionals.

## Features
- **Disease Prediction**: Predicts the likelihood of diseases based on patient symptoms.
- **Machine Learning Models**: Logistic Regression, Decision Trees, Random Forest, SVM, and Adaptive Boosting are used.
- **Feature Selection**: Uses backward selection and p-value testing to determine important features.
- **Web Application**: Built using the Django framework for frontend and SQLite for backend data storage.
- **Email Notifications**: The system sends email notifications with disease prediction results to patients.

## Objectives
- Develop a diagnostic tool for early-stage disease detection, particularly coronary heart disease.
- Increase efficiency by working with larger datasets and reduce the need for excessive medical testing.

## Technologies Used
- **Frontend**: Django Web Framework, HTML5, CSS, Bootstrap 4
- **Backend**: SQLite
- **Programming Language**: Python 3.x
- **Machine Learning Libraries**: NumPy, Pandas, Scikit-learn

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Disease-Prediction-using-ML-algorithms.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Disease-Prediction-using-ML-algorithms
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up the Django server:
    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

## Usage

1. **For Doctors**:
   - Log in using credentials.
   - Enter patient test data to predict diseases.
   - View predictions and confusion matrices for each disease.

2. **For Patients**:
   - Log in using the credentials received via email.
   - View the results of your disease predictions and suggested treatments.

## Datasets
The datasets for this project are sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). These datasets contain medical records for diseases like heart disease, lung cancer, and diabetes.

## Future Enhancements
- Improve prediction accuracy by experimenting with additional algorithms like Naive Bayes and K-Nearest Neighbors.
- Expand the system to include recommendations for early treatment and prevention based on patient data.
- Develop this into a comprehensive healthcare diagnosis system for hospital use.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please contact [Shaik Jahir Abbas](mailto:shaik.jahirabbas2016@gmail.com).
