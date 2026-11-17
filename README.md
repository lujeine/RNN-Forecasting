# RNN Time-Series Forecasting with PyTorch

Forecasting hourly air pollution (PM2.5) with a configurable vanilla RNN / GRU / LSTM,
using the Kaggle dataset
[Air Pollution Forecasting - LSTM Multivariate](https://www.kaggle.com/datasets/rupakroy/lstm-datasets-multivariate-univariate).


## Reproduce
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt

# download the CSV from Kaggle (website, or `kaggle datasets download rupakroy/lstm-datasets-multivariate-univariate`)
# and place it in this folder, e.g. pollution.csv

jupyter notebook rnn_forecasting.ipynb        # or:
python rnn_forecasting.py --data pollution.csv --target pollution
```
The notebook also runs on Kaggle or Colab with a GPU.


