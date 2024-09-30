# **Stock Market Prediction using Candlestick Chart Analysis and Machine Learning**

This project aims to predict stock price movements based on candlestick chart patterns using machine learning techniques. By leveraging Python libraries such as `yfinance`, `mplfinance`, and TensorFlow, the project builds a pipeline to visualize stock data, create candlestick charts, and train a Convolutional Neural Network (CNN) to classify price movements.

## **Project Overview**

The project was developed through multiple iterations, gradually refining the approach to improve accuracy and performance:

1. **Manual Chart Uploads**:  
   Initially, candlestick charts were manually generated and uploaded into the model for classification. The model was trained using a limited set of manually processed images to identify stock price movements (increase, decrease, neutral).

2. **Automated Chart Generation**:  
   The next step automated the process by using Python to retrieve stock market data via `yfinance` and visualize it using `mplfinance`. Candlestick charts were created programmatically, and then fed into the machine learning model for training and testing.

3. **Mass Chart Production**:  
   To enhance the dataset, the project scaled up by producing numerous candlestick charts for different time frames and stock symbols. Random date ranges were selected to create a diverse dataset for more robust training and evaluation.

4. **Model Refinement and Training**:  
   The Convolutional Neural Network (CNN) was refined in this stage, incorporating improvements in data preprocessing, feature extraction, and hyperparameter tuning. The model architecture was expanded to include multiple convolutional and pooling layers, optimized for time-series data.

5. **Training and Validation Separation**:  
   The final iteration involved splitting the data into separate training and validation sets to ensure a more accurate evaluation of the model's performance. The model was further fine-tuned using real-time backtesting and performance metrics such as accuracy and loss.

## **Role in Finance Club Quant Team**

This project was part of a [larger initiative](https://github.com/DFIC-Quant-Fund/CompVision-W2024) with the Quant Group at the [**DeGroote Finance and Investments Council**](https://www.degrootefinance.ca/). The team worked on various aspects of algorithmic trading strategies, and I was responsible for **refining the machine learning model** in this project. While other team members focused on different aspects of the project, such as supplying data, refining the strategy and backtesting, I was tasked with creating the data pipeline and developing an accurate model. 

Although the project is currently **unfinished**, the groundwork has been laid to build a robust, data-driven model for predicting stock market trends using machine learning.

## **Technologies Used**
- **Python**: Core language for data retrieval, chart generation, and machine learning implementation.
- **`yfinance`**: Used to download historical stock data for multiple symbols.
- **`mplfinance`**: Visualized stock data as candlestick charts.
- **TensorFlow & Keras**: Built and trained a Convolutional Neural Network (CNN) to classify stock price movements.
- **Pandas**: Handled time-series data processing.
- **NumPy**: Performed data normalization and array manipulation.

## **Project Workflow**
1. Download stock data for selected symbols and time frames.
2. Generate candlestick charts based on the stock data.
3. Label charts according to stock price movements (increase, decrease, neutral).
4. Train a CNN on labeled chart images, optimizing the model architecture over multiple iterations.
5. Evaluate the model's performance using a validation set.

## **Results**
The final model achieved an improved classification accuracy by utilizing a well-balanced dataset, refined model architecture, and carefully split training and validation data. The approach demonstrates the potential of using historical stock charts for market prediction via machine learning.

---

This project is currently a **work in progress** and will be further refined in future iterations.
