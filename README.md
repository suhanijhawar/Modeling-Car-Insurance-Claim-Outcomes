
# Car Insurance Claim Prediction

## Project Overview
This project involves building a machine learning model to predict whether a customer will make a claim on their car insurance during the policy period. The project is requested by **On the Road car insurance**, and the goal is to identify the single feature that results in the best-performing model in terms of accuracy. This will help the company start with a simple, easy-to-deploy model in production.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Goal](#goal)
- [Installation](#installation)
- [Feature Selection](#feature-selection)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The dataset (`car_insurance.csv`) contains customer data with the following columns:

| Column | Description |
|--------|-------------|
| `id` | Unique client identifier |
| `age` | Client's age (grouped into categories) |
| `gender` | Client's gender |
| `driving_experience` | Years of driving experience (grouped into ranges) |
| `education` | Client's level of education |
| `income` | Client's income level |
| `credit_score` | Client's credit score (between 0 and 1) |
| `vehicle_ownership` | Client's vehicle ownership status |
| `vehicle_year` | Year of vehicle registration |
| `married` | Client's marital status |
| `children` | Client's number of children |
| `postal_code` | Client's postal code |
| `annual_mileage` | Number of miles driven by the client each year |
| `vehicle_type` | Type of vehicle (Sedan or Sports car) |
| `speeding_violations` | Number of speeding violations |
| `duis` | Number of DUI offenses |
| `past_accidents` | Number of previous accidents |
| `outcome` | Whether the client made a claim (response variable) |

## Goal
The objective of this project is to determine which single feature results in the most accurate model for predicting whether a customer will make an insurance claim during the policy period.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/car-insurance-claim-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd car-insurance-claim-prediction
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Feature Selection
To meet the company's request, feature selection is performed to identify the single feature that provides the best model performance. This will involve:
- Exploratory Data Analysis (EDA)
- Feature importance ranking (e.g., using decision trees or correlation metrics)
- Evaluation of each feature's impact on model accuracy.

## Modeling
The following machine learning models are used for experimentation:
- **Logistic Regression**
- **Decision Trees**
- **Random Forest**
- **Support Vector Machines (SVM)**

Models are trained using individual features, and the one that yields the highest accuracy is selected.

## Results
The results of the analysis will include:
- The feature that provides the best predictive performance.
- The accuracy of the best model.
- Recommendations for model deployment.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
