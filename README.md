# Placement__Prediction--Using-Machine-Learning 
The project aims to predict the likelihood of a student being placed in a company based on historical placement data, academic records, and relevant skills of students. It provides valuable insights to both students and recruiters, enhancing the placement process and increasing overall job satisfaction. [Visit here](https://yashaswiniproject101.onrender.com)<br>

## Overview

This Flask-based project utilizes a Logistic Regression model to predict job placements for students. It features a web interface where users can input their academic and personal details to obtain a prediction regarding their likelihood of being placed.

### Dataset and Features

The project employs a dataset containing various features:

- gender
- ssc_p: Secondary Education percentage
- hsc_p: Higher Secondary Education percentage
- hsc_s: Specialization in Higher Secondary Education
 degree_p: Degree percentage
- degree_t: Type of Undergraduate Degree
- workex: Work experience
- etest_p: Employability test percentage
- specialisation: MBA specialization
- mba_p: MBA percentage

  
## Features

- **Prediction Route**: `/send` accepts form inputs and predicts placement chances.
- **User Interface**: HTML templates (`index.html`, `predict.html`, `show.html`) for user interaction.
- **Model**: `logreg_model.pkl` file contains the trained Logistic Regression model.

## Setup

### Prerequisites

- Python 3.x
- Flask
- NumPy
- Pandas
- scikit-learn

### Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/YashaswiniJawalkar/Placement__Prediction--Using-Machine-Learning.git
    cd student-placement
    ```

2. **Virtual Environment and Dependencies**

    ```bash
    conda create --prefix ./env_name python=3.6
    conda activate ./env_name
    pip install flask numpy pandas scikit-learn
    ```

3. **Run the Application**

    ```bash
    python app.py
    ```

## Usage

1. **Homepage**

    Open a web browser and visit `http://localhost:5000/` to access the home page.

2. **Input Details**

    Enter academic and personal details into the form.

3. **Prediction**

    Click 'Predict' to obtain the system's placement prediction.

## File Structure

- **`app.py`**: Contains Flask application code.
- **`logreg_model.pkl`**: The Logistic Regression model for predictions.
- **`templates/`**: HTML templates for the user interface.
- **`static/`**: Directory for static files (CSS, images, etc.).

## Visit Website 

[Click Here](https://yashaswiniproject101.onrender.com) to visit project

## Conclusion

The Student Placement Prediction System uses a Logistic Regression model in Flask to estimate the likelihood of a student securing a job placement based on their academic and personal details.
