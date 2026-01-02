## Project Overview

Accurately forecasting weekly sales is critical for any company, with this we can optimize inventory, plan promotions, and avoid stockouts. In this project we developed a machine learning model to predict weekly sales at the store and department level using historical sales data, holiday information, and external economic indicators.

Through exploratory data analysis (EDA) based on hypotheses, we formulated and validated assumptions about sales patterns, seasonality, and holiday effects. We applied preprocessing methods such as feature scaling and feature selection to enhance model performance. Models such as Random Forest and XGBoost were trained and evaluated using MAE, RMSE, and R² metrics.

## Impact

Our best model achieved a mean absolute percentage error (MAPE) of approximately 13.6% in forecasting weekly sales, indicating reasonably accurate sales projections, with that, we can consult and send this information for every store to plan for the week.

| Model Name              | MAE        | MAPE   | RMSE       |
| ----------------------- | ---------- | ------ | ---------- |
| XGBRegressor            | 119,675.03 | 13.64% | 177,380.48 |
| Random Forest Regressor | 127,777.60 | 14.01% | 234,441.24 |

