# Madrid Air Quality LSTM Forecasting

This project implements a Long Short-Term Memory (LSTM) network in PyTorch to forecast air pollutant levels (NO₂ and NOx) using hourly data from Madrid's air quality monitoring stations (2001–2018).

## Key Features
- Data exploration and station coverage analysis
- Preprocessing with sliding window sequences
- LSTM training on high-coverage station
- **Extension 1**: Testing generalization on other high-coverage stations
- **Extension 2**: Multi-station training (3 stations) showing improved performance on unseen stations

## Dataset
Kaggle: [Air Quality in Madrid (2001-2018)](https://www.kaggle.com/datasets/decide-soluciones/air-quality-madrid)

## Requirements
```bash
pip install torch pandas numpy matplotlib scikit-learn
