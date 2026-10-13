# Nigerian Agricultural Commodity Price Forecasting

An interactive data science application for exploring historical agricultural commodity prices and comparing machine-learning and time-series forecasting models for Nigerian agricultural markets.

**[Launch the Live App](https://agricultural-price-forecasting-kjqdtjcacpvqrun6r4pguw.streamlit.app/)** · **[View the Source Code](https://github.com/walexgee/agricultural-price-forecasting)**

## Project Overview

Agricultural commodity prices can fluctuate over time, making historical price analysis and forecasting useful for understanding market trends. This project applies data analysis and forecasting techniques to Nigerian agricultural commodity price records.

The project includes a Streamlit web application that allows users to explore historical price patterns, compare model performance, examine five-year forecasts, and review backward-validation results.

This project was developed as an academic data science project and demonstrates the application of Python, time-series analysis, model evaluation, and interactive data visualization to an agricultural economics problem.

## Live Application

**Try the application:**
https://agricultural-price-forecasting-kjqdtjcacpvqrun6r4pguw.streamlit.app/

The application has four main sections:

* **Overview:** Explore the project and its agricultural price data.
* **Model Comparison:** Compare Linear Regression, Support Vector Regression, and Prophet using model evaluation metrics.
* **5-Year Forecast:** Explore projected commodity prices over a five-year horizon.
* **Backward Validation:** Examine historical forecasting performance over a past period.

## Models and Evaluation

The project compares three forecasting approaches:

| Model                           | Description                                                                       |
| ------------------------------- | --------------------------------------------------------------------------------- |
| Linear Regression (LR)          | Models relationships between input features and prices using a linear function.   |
| Support Vector Regression (SVR) | Uses support vector methods to model relationships that may be nonlinear.         |
| Prophet                         | A time-series forecasting model designed to capture temporal patterns and trends. |

Model performance is evaluated using:

* **Mean Absolute Error (MAE):** The average absolute difference between actual and predicted prices.
* **Root Mean Squared Error (RMSE):** The square root of the average squared prediction error, giving larger errors more influence.
* **Mean Absolute Percentage Error (MAPE):** The average absolute prediction error expressed as a percentage, subject to limitations when actual values are zero or close to zero.

The metrics support a quantitative comparison of forecasting performance. The most suitable model should be identified from the evaluation results rather than assumed in advance.

## Technology Stack

* **Python** — data processing and model implementation
* **Pandas** — data manipulation and preprocessing
* **Scikit-learn** — machine-learning models and evaluation
* **Prophet** — time-series forecasting
* **Streamlit** — interactive web application
* **Plotly** — interactive charts and data visualization

## Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/walexgee/agricultural-price-forecasting.git
cd agricultural-price-forecasting
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

On Windows:

```bash
.venv\Scripts\activate
```

### 3. Install the dependencies

Install the project's dependencies using its `requirements.txt` file, if present:

```bash
pip install -r requirements.txt
```

If the repository does not contain a `requirements.txt` file, create one using the packages and versions required by the application before following this step.

### 4. Start the Streamlit application

From the repository root, run:

```bash
streamlit run uilfyp/app.py
```

If the application uses files stored in `uilfyp/`, keep the repository's directory structure intact when running it.

## Repository Structure

The application and its supporting data are located in the `uilfyp/` directory.

```text
agricultural-price-forecasting/
└── uilfyp/
    ├── app.py
    └── forecast_data.json
```

The directory listing above shows the main application files; other project files, datasets, notebooks, and dependencies may also be present in the repository.

## Scope and Limitations

Forecasts are estimates based on the historical information and modelling assumptions used in the project. They are not guaranteed future prices.

External influences such as inflation, exchange rates, government policies, weather conditions, transportation costs, and market disruptions may affect actual prices. Unless these factors are explicitly represented in the model, their future effects cannot be reliably inferred from the forecasts alone.

Backward-validation results provide evidence about historical forecasting performance, but they do not guarantee the same level of accuracy in future periods.

## Future Improvements

Potential extensions include:

* Incorporating relevant external economic and environmental variables.
* Evaluating models across different commodities and market locations.
* Adding automated model testing and reproducible evaluation.
* Improving forecast uncertainty reporting and model monitoring.

LAWAL RIDWANULAHI OLAWALE

**Walexgee**

GitHub: https://github.com/walexgee

---

*This project is intended for academic demonstration and exploratory analysis. Forecasts should not be treated as guaranteed market prices or financial advice.*
