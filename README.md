# Data-mining-project-spring-semester
# Final Project

## Date
2023-03-31

## Description
This repository contains all materials related to the final project. The project endeavors to predict the outcomes of university students in Portugal (graduate, stay enrolled, or drop out) utilizing a range of features including demographic, socioeconomic, and academic data. Employing machine learning methods, we aim to create a model that accurately identifies patterns and potential determining factors in student outcomes.

### Dataset
- **Source:** The dataset is adapted from an article by Realinho et al. (2022).
- **Columns:**
    - `student_id`: Unique identifier for each student.
    - `gender`: Gender of the student.
    - `socioeconomic_status`: Socioeconomic background indicator.
    - `highschool_gpa`: Grade Point Average from high school.
    - `attendance`: Attendance rate during the course.
    - `participation`: Level of participation in classes and extracurricular activities.
    - `midterm_grade`: Midterm grade in university.
    - `final_grade`: Final grade in university.
    - `outcome`: Student outcome (graduate, enrolled, drop out).
    - [Add additional column descriptions as per your dataset...]
    
### Methods
- **LightGBM:** LightGBM is a gradient boosting framework that uses tree-based learning algorithms. It is designed to be distributed and efficient with the following advantages: faster training speed and higher efficiency, lower memory usage, better accuracy, support of parallel and GPU learning, and capable of handling large-scale data. In this project, LightGBM will be utilized to predict the outcomes based on the features provided in the dataset, taking into account the potential non-linear relationships and interactions between different variables.

## Usage
1. **Data Preparation:**
    - Ensure the data is placed in the `Data/` directory, adhering to the structure described above.
    - Ensure you have R and all the necessary libraries installed. You can install the libraries using the `install.packages()` function in R.
    
2. **Running the Code:**
    - Navigate to the `Code/` directory and run the scripts in the following order: 
        1. `data_cleaning.R`: To preprocess the data.
        2. `eda.R`: For exploratory data analysis.
        3. `modeling.R`: To train the LightGBM model and evaluate its performance.
    - Alternatively, if using a notebook: execute cells in order to prevent any runtime issues.

3. **Visualizing Results:**
    - Check the `Figures/` directory for generated plots and visualizations.
    - Refer to the `Results/` directory for model outcomes and predictions.

4. **Contributing:**
    - For collaboration or contribution, please refer to the CONTRIBUTING.md file for guidelines. [Note: You might create a CONTRIBUTING.md file with clear guidelines if you want to allow others to contribute.]

## Contributors
- ** Shalon Walter, Swetha Siripurappu, Tung Phung** 


