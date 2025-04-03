# **Stock Market Forecasting using Stacked LSTM (Deep Learning)**  

## **Overview**  
This project utilizes a **Stacked Long Short-Term Memory (LSTM)** deep learning model to predict stock prices. The model is trained on historical stock market data and forecasts future prices based on past trends.  

## **Features**  
- Uses **Stacked LSTM** for time series forecasting  
- Data preprocessing, including normalization and scaling  
- Visualization of stock trends and predictions  
- Evaluation metrics for model performance  

## **Dataset**  
The project uses stock market data stored in **AAPL.csv**. The dataset includes:  
- Date  
- Open, High, Low, Close prices  
- Volume  

## **Installation & Setup**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/mishraShilpa-28/stock-market-forecasting.git
   cd stock-market-forecasting
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```  
   Open `main.ipynb` and run the cells.  

## **Model Architecture**  
- **Input Layer**: Takes historical stock price data  
- **Stacked LSTM Layers**: Extract temporal dependencies  
- **Dense Layer**: Outputs the predicted stock price  

## **Usage**  
1. Load historical stock data  
2. Train the LSTM model  
3. Visualize predictions vs. actual stock prices  
4. Use the model to forecast future stock trends  

## **Results**  
The model successfully predicts future trends based on historical data, providing valuable insights for stock market analysis.  

## **Contributing**  
Feel free to contribute by improving the model, adding new features, or optimizing performance.  

## **License**  
This project is open-source under the MIT License.
