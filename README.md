# Time Series Analysis Project

This project contains various tasks related to time series analysis, including generating synthetic time series data, performing stationarity tests, differencing, and plotting ACF and PACF plots. The project is divided into multiple tasks, each focusing on different aspects of time series analysis.

## Project Structure

- `task1.py`: Generate AR models, check stationarity, and plot time series.
- `task2.py`: Generate AR models, plot time series, histograms, density plots, box plots, lag plots, and ACF/PACF plots.
- `task3.py`: Generate MA models, plot time series, histograms, density plots, box plots, lag plots, and ACF/PACF plots.
- `task4.py`: Generate ARMA models, plot time series, histograms, density plots, box plots, lag plots, and ACF/PACF plots.
- `task5.py`: Perform various tests and plots on temperature change data, including Ljung-Box test, ADF test, differencing, and model fitting.
- `task6.py`: Remove linear, exponential, and seasonal trends from synthetic time series data, perform ADF tests, and plot differenced series and ACF plots.
- `data.csv`: Contains the synthetic time series data and temperature change data.
- `output.csv`: Contains the test results from `task5.py`.

## Requirements

- Python 3.11
- numpy
- pandas
- matplotlib
- seaborn
- statsmodels
- scikit-learn

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Xqzhang-uestc/MICS6001M-Assignment2.git
    cd MICS6001M-Assignment2
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Task 1

Generate AR models, check stationarity, and plot time series:

```bash
python task1.py
```



### Task 2

Generate AR models, plot time series, histograms, density plots, box plots, lag plots, and ACF/PACF plots:

```bash
python task2.py
```

### Task 3

Generate MA models, plot time series, histograms, density plots, box plots, lag plots, and ACF/PACF plots:
    
```bash
python task3.py
```

### Task 4
Generate ARMA models, plot time series, histograms, density plots, box plots, lag plots, and ACF/PACF plots:
    
```bash
python task4.py
```

### Task 5
Perform various tests and plots on temperature change data, including Ljung-Box test, ADF test, differencing, and model fitting:

```bash
python task5.py
```

### Task 6
Remove linear, exponential, and seasonal trends from synthetic time series data, perform ADF tests, and plot differenced series and ACF plots:
    
```bash
python task6.py
```

## Author
- Student1: Xianqing Zhang(50019300)
- Student2: Wenjuan Zhou(50019984)

## Result
The results of the tests and plots are saved in the `pics` directory. The test results from `task5.py` are saved in `output.csv`.
