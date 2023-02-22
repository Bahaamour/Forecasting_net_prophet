# Forecasting_net_prophet

![An image for the header of the Repository](/Images/MecroLibre.png)

This application helps MicroLebre in the following:
- Visualize depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
- evaluation of how the company’s stock price correlates to its Google Search traffic.
- Prophet forecast model that predicts hourly user search traffic.
- A plot of a forecast for the company’s future revenue.




## Technologies
This platform uses `python 3.7.13` with the following libraries imported in the first code block includes: `Pandas`, `hvplot`, `scikit-learn`, `pathlib`, and Facebook `Prophet` library.

---
## Installation Guide 

In case Pandas library is not available, run the following code in your terminal:

```python

pip install pandas
```


To install `scikit-learn`, `hvplot`, `Prophet` make sure your Conda `dev` environment is active, run the following command:

```python
pip install -U scikit-learn
```

```python
pip install -c pyviz hvplot
```

```python
pip install prophet
```

To confirm the  installation, run the following code in your terminal:

```python
conda list scikit-learn
conda list hvplot
 ```
 
---

## Usage

Libraries that we had to import are the following:

```
import pandas as pd
from prophet import Prophet
import hvplot.pandas
import datetime as dt 
%matplotlib inline 
import holoviews as hv
import seaborn as sns
import warnings
warnings.filterwarnings("ignore")
```

---
## Contributors

Baha Amour
---

## License

MIT.