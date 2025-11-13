# Signal Analysis using Linear Predictive Coding (LPC)

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Librosa](https://img.shields.io/badge/Librosa-0.8.1-red)](https://librosa.org/)
[![Statsmodels](https://img.shields.io/badge/Statsmodels-0.12.2-blue)](https://www.statsmodels.org/)

<img width="310" height="390" alt="ChatGPT Image Nov 12, 2025, 04_13_14 PM" src="https://github.com/user-attachments/assets/1b339910-e583-4caf-849c-9df6b0b7e85c" />

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
