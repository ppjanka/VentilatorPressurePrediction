# VentilatorPressurePrediction

Full data and model exploration notebook to predict medical ventilator pressure based on (patient-specific) past ventilator state data. Created for the [Google Brain - Ventilator Pressure Prediction competition](https://www.kaggle.com/c/ventilator-pressure-prediction) hosted by [Kaggle](https://kaggle.com).

The original notebook (with version history and connection to the relevant data sources) is availabile [on Kaggle Notebooks](https://www.kaggle.com/ppjanka/2021-gbrain-ventilpress).

**Contents:**
 - initial exploration of time-series data,
 - regression models using time-series data:
    - linear regression,
    - SGDR,
    - vanilla dense neural network,
    - LSTM, RNN, GRU,
    - ensemble methods: boosting,
 - hyperparameter tuning:
    - keras_tuner.
