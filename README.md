# Signal Analysis using Linear Predictive Coding (LPC)

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Librosa](https://img.shields.io/badge/Librosa-0.8.1-red)](https://librosa.org/)
[![Statsmodels](https://img.shields.io/badge/Statsmodels-0.12.2-blue)](https://www.statsmodels.org/)

<img width="524" height="786" alt="ChatGPT Image Nov 12, 2025, 04_13_14 PM" src="https://github.com/user-attachments/assets/cbfae2bd-6c31-4e6d-9a2d-ccbf61fe6d39" />

A Python project for signal analysis and time-series estimation using Linear Predictive Coding (LPC). This project is implemented in a Jupyter Notebook and utilizes libraries such as Librosa and Statsmodels to model signals and evaluate estimation errors.

## About The Project

This project explores the implementation of the LPC (Linear Predictive Coding) model for analyzing and predicting time-series signals. The primary goal is to compare the signal estimated by the LPC model against the original signal and calculate the Mean Squared Error (MSE) to evaluate the model's accuracy, particularly as the number of poles (model order) changes.

### Files & Data

* `code.ipynb`: The main Jupyter Notebook containing all the code, analysis, and visualizations.
* `doc.pdf`: (Optional) Project documentation or report.
* `kond.csv` & `tond.csv`: The time-series signal data used for the analysis.

## Technologies Used

This project was developed using the following tools and libraries:

* **Python 3**
* **Jupyter Notebook**
* **Numpy**: For numerical computations.
* **Scipy**: For scientific functions, including `signal.lfilter`.
* **Librosa**: For audio and signal processing, specifically for the `librosa.lpc` function.
* **Statsmodels**: For statistical analysis and time-series models.
* **Matplotlib**: For plotting graphs and data visualization.
* **Scikit-learn**: For calculating the `mean_squared_error`.

## Getting Started

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/](https://github.com/)[YOUR_USERNAME]/[YOUR_REPOSITORY_NAME].git
    cd [YOUR_REPOSITORY_NAME]
    ```
    *(Remember to replace `[YOUR_USERNAME]` and `[YOUR_REPOSITORY_NAME]`)*

2.  **Create and activate a virtual environment (Recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install dependencies:**
    (It's a good practice to create a `requirements.txt` file from these)
    ```sh
    pip install jupyter numpy scipy librosa statsmodels matplotlib scikit-learn
    ```

4.  **Run the Jupyter Notebook:**
    ```sh
    jupyter notebook code.ipynb
    ```
## Key Results

(You can add a summary of your findings here, perhaps including the plot showing MSE vs. the number of poles.)

This analysis demonstrates how LPC can be effectively used to model a signal. The results in `code.ipynb` show the relationship between the model order (number of poles) and the accuracy of the signal estimation, visualized by plotting the Mean Squared Error.
