# Flight Prices Prediction

This project is a Flight Prices Prediction web application developed using Flask and deployed on Render. The application utilizes machine learning models to predict flight prices based on various factors.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used

- **Flask**: A lightweight WSGI web application framework.
- **Pandas**: A data manipulation and analysis library.
- **NumPy**: A library for numerical operations.
- **Scikit-learn**: A machine learning library for Python.
- **Random Forest**: The primary model used for predictions.
- **SVR**: Support Vector Regression model.
- **XGBoost**: An optimized distributed gradient boosting library.

## Features

- Predict flight prices based on historical data.
- User-friendly interface for inputting parameters.
- Visualization of predictions and model performance.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   `git clone <repository-url>`

2. Navigate to the project directory:
   `cd flight-prices-prediction`

3. Install the required packages:
   `pip install -r requirements.txt`

4. Run the Flask app:
   `gunicorn app:app`

## Usage

After starting the Flask app, navigate to [http://localhost:5000](http://localhost:5000) in your web browser to access the application. You can also access the deployed app at [https://flask-ml-project-v4al.onrender.com](https://flask-ml-project-v4al.onrender.com). Input the required parameters to get flight price predictions.


## Models Used

The following machine learning models were implemented in this project:

- **Linear Regression**
- **Random Forest** (Best performing model)
- **Support Vector Regression (SVR)**
- **XGBoost**

## Results

The Random Forest model demonstrated the best performance in predicting flight prices. Below are visual representations of the model's performance:

![Model Performance](https://github.com/Prasad2357/flask-ml-project/blob/master/Images/Home_Page.png)

![Price Predictions](https://github.com/Prasad2357/flask-ml-project/blob/master/Images/Predict.png)

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Instructions

- Ensure you replace `<repository-url>` with your actual repository URL.
- Update the image links with the actual URLs where your images are hosted.

Feel free to modify any section as per your preferences!
