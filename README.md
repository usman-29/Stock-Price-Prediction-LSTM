# Google Stock Price Prediction

## Project Overview

GOOGL, or Google’s stock, is a highly favored investment option due to:
- **Strong Financial Results**: Reflecting the company's excellent performance.
- **Dominance in the Tech Sector**: A leader in innovation and market presence.

This project aims to predict Google's stock prices using historical data and advanced machine learning techniques, focusing on building a Long Short-Term Memory (LSTM) model for accurate forecasts.

---

## Dataset Details

The **Google Stock Price Dataset** includes historical pricing data from **June 14, 2016**, to **September 21, 2024**. The dataset contains the following variables:

| Variable Name   | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **Open**         | Stock's opening price on a given date                                      |
| **High**         | Highest price the stock traded at during the day                          |
| **Low**          | Lowest price the stock traded at during the day                           |
| **Close**        | Stock's closing price on a given date                                     |
| **Volume**       | Total number of shares traded on that date                                |
| **Dividends**    | Cash distributions to shareholders that may lower the stock price         |
| **Stock Splits** | Division of shares to improve affordability and liquidity without value change |

---

## Methodology

1. **Data Preprocessing**:
   - Imported and cleaned data using `pandas` and `numpy`.
   - Normalized the data using `MinMaxScaler` for better performance.

2. **Model Architecture**:
   - Built an LSTM-based sequential model using TensorFlow/Keras.
   - The architecture includes:
     - LSTM layers with 64 and 32 units.
     - Fully connected Dense layers for output.
     - Mean Squared Error (MSE) as the loss function.
     - Adam optimizer for model compilation.

3. **Training**:
   - Model trained for 50 epochs with a batch size of 32.
   - Used a validation set to monitor performance during training.

4. **Libraries Used**:
   - `numpy`, `pandas`, `seaborn`, `matplotlib`, `tensorflow`, `keras`
   - Data visualization enhanced with `plotly.graph_objects`.

---

## Result

<img src="https://github.com/user-attachments/assets/6db36287-a2df-4bdb-a85b-c9b43442a036" alt="Screenshot 2024-11-27 134156" width="800">



