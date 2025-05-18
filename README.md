# Time Series Analysis and Forecasting for Stock Market

This project involves analyzing historical stock market data and forecasting future trends using statistical and machine learning models. The goal is to gain insights into market behavior and build predictive models using time series techniques.

---

## Project Setup & Installation

Follow these instructions to set up the project environment and install all necessary dependencies.

### 1. Clone the Repository (if using Git)
```bash
git clone https://github.com/shalommathew/time-series-stock-forecast.git
cd time-series-stock-forecast
```

### 2. Create and Activate a Virtual Environment
```bash
# Create virtual environment
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on macOS/Linux
source venv/bin/activate
```

### 3. Install Required Dependencies
Create a `requirements.txt` file (already included) and run:

```bash
pip install -r requirements.txt
```

### 4. Requirements.txt
Here are the core dependencies:
```txt
pandas
numpy
matplotlib
seaborn
plotly
yfinance
scikit-learn
statsmodels
prophet
tensorflow
jupyter
```

> ⚠️ **Note**: If Prophet fails to install, you may need to install `pystan` or `cmdstanpy` depending on your OS. Refer to [Prophet installation guide](https://facebook.github.io/prophet/docs/installation.html).

### 5. Folder Structure
```
time-series-stock-forecast/
├── data/                    # Raw and cleaned data
├── notebooks/               # Jupyter notebooks for analysis
├── docs/                    # Documentation and notes
├── venv/                    # Virtual environment (not pushed to Git)
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

### 6. Open in VSCode
Open the folder in VSCode and select the appropriate Python interpreter from your `venv`.

### 7. Run Jupyter Notebooks
Install the Jupyter extension in VSCode and open notebooks directly, or run:
```bash
jupyter notebook
```

---

## Tech Stack & Tools
- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, Statsmodels, Prophet, TensorFlow/Keras
- **Visualization**: Plotly, Seaborn, Matplotlib
- **Deployment (Optional)**: Streamlit / Flask

---

## License
This project is for educational purposes only. Modify and adapt as needed.

---

## Author
- [Shalom Mathew](https://github.com/shalommathew)
