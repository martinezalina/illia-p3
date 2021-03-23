
# AU Illia CABA
#### Time Series Forecasting



## Objetivo

El objetivo de este proyecto es predecir el tránsito vehicular de la AU Illia (CABA), a partir de los datos históricos de la misma.

## Datos

https://data.buenosaires.gob.ar/dataset/flujo-vehicular-por-unidades-peaje-ausa

## EDA

- Time Series resample
- Missing Values
- Atypical Values / Outliers
- Autocorrelation
- Seasonal Components (Additive / Multiplicative)
- Residual histogram

## Models

- Benckmark: Pandas Rolling Windows Mean
- XGBoost Regressor 
- XGBoost Regressor + GridSearchCV
- LSTM