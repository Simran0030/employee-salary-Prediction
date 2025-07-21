# employee-salary-Prediction
# Employee Salary Data Analysis
# https://b4568030bd1b.ngrok-free.app/
## Overview
This Jupyter Notebook contains an analysis of employee salary data with various attributes including years of experience, education level, job role, city, and salary. The dataset is synthetically generated for analysis purposes.

## Dataset Description
The dataset includes 100 employees with the following attributes:
- **YearsExperience**: Randomly generated values between 1 and 20 years
- **EducationLevel**: Categorical values ('High School', 'Bachelor's', 'Master's', 'PhD')
- **JobRole**: Categorical values ('Engineer', 'Data Scientist', 'Manager', 'Analyst')
- **City**: Categorical values ('New York', 'Los Angeles', 'Chicago', 'Houston')
- **Salary**: Randomly generated values between $40,000 and $150,000, with adjustments based on years of experience
- **Age**: Randomly generated values between 20 and 65
- **Name**: Randomly generated employee names

## Key Features
1. **Data Generation**: The dataset is created using Python's NumPy and Pandas libraries with realistic distributions.
2. **Data Exploration**: Basic exploration includes checking for null values, value counts for categorical variables, and summary statistics.
3. **Data Visualization**: Histograms are used to visualize the distribution of age and years of experience.
4. **Feature Engineering**: Additional columns like 'Age' and 'Name' are added to enhance the dataset.

## Usage
1. **Requirements**: Python 3, Pandas, NumPy, Matplotlib
2. **Installation**: Clone the repository and install the required packages using `pip install -r requirements.txt`.
3. **Execution**: Run the Jupyter Notebook to regenerate the dataset or perform analysis.

## Insights
- The dataset shows a correlation between years of experience and salary.
- Education levels are distributed with Bachelor's degree being the most common.
- The majority of employees are located in New York.

## Future Work
- Perform more detailed statistical analysis.
- Build predictive models for salary based on other attributes.
- Add more features like department or performance metrics.

## License
This project is open-source and available for anyone to use and modify.
