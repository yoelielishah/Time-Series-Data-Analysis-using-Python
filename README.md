# Analyzing Stationary and Unstationary Time Series Data Using Python

This project demonstrates the concepts of stationarity in time series data by comparing the properties of generated stationary and non-stationary time series using Python.

## Project Overview

The goal of this project is to visually and statistically illustrate the key differences between stationary and non-stationary time series data. This is achieved by:

1.  **Generating Synthetic Data:** Creating sample datasets for both stationary and non-stationary time series.
2.  **Analyzing Key Properties:** Calculating and visualizing the mean, variance, and Autocorrelation Function (ACF) for each type of time series.
3.  **Illustrating with Rolling Statistics:** Using rolling window calculations for mean and variance to highlight their behavior over time for both data types.
4.  **Visualization:** Employing plots to clearly show the characteristics of stationary and non-stationary data and the results of the analysis.

## Getting Started

To run this analysis, you can use a Google Colab notebook or a local Python environment with the necessary libraries installed.

### Using Google Colab

The code is designed to be run in a Google Colab environment.

1.  Open a new Google Colab notebook.
2.  Copy and paste the code from the `Analyzing Stationary and Unstationary Time Series Data Using Python.ipynb` notebook into the Colab cells.
3.  Run the cells sequentially.

### Local Python Environment

If you prefer to run the code locally, you'll need to have Python installed along with the following libraries:

*   `numpy`
*   `pandas`
*   `matplotlib`
*   `statsmodels`

You can install these libraries using pip:


Once the libraries are installed, you can run the code from your Python environment.

## Code Explanation

The notebook is structured into sections that cover:

*   **Introduction:** Explaining the project's objective.
*   **Generating Stationary Data:**
    *   Creating random data using `numpy`.
    *   Calculating and printing mean and variance.
    *   Plotting the data.
    *   Calculating and plotting the ACF using `statsmodels`.
    *   Calculating and plotting rolling mean and variance using `numpy.convolve` and `pandas.rolling`.
*   **Generating Non-Stationary Data:**
    *   Creating data with a linear trend and random noise.
    *   Plotting the data to show the trend.
    *   Calculating and plotting rolling mean and variance.
    *   Calculating and plotting the ACF using `statsmodels`.

## Analysis and Results

The plots and calculated statistics demonstrate the core concepts:

*   **Stationary Data:** Exhibits a relatively constant mean and variance over time, and its ACF drops off quickly.
*   **Non-Stationary Data:** Shows a changing mean and variance (often a clear trend), and its ACF decays slowly.

These characteristics highlight why stationarity is an important assumption for many time series forecasting models.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request.

## License

MIT License

## Contact

If you have any questions or feedback, please feel free to reach out.

[Elisha Yoeli / (https://github.com/yoelielishah) / elis.yoeli@gmail.com ]
