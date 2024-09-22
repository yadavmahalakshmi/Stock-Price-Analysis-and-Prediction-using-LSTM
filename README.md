## Stock-Price-Analysis-and-Prediction-using-LSTM

# PROJECT OVERVIEW
The Stock Price Analysis and Prediction project utilizes advanced machine learning models, including LSTM (Long Short-Term Memory), GRU (Gated Recurrent Units), and ConvLSTM (Convolutional LSTM), to forecast future stock prices for major technology companies. The project is built around analyzing historical stock data, visualizing stock trends, and applying various technical indicators such as RSI, MACD, Bollinger Bands, and Moving Averages to provide comprehensive insights. Furthermore, it leverages real-time stock data fetched via the Yahoo Finance API to predict stock prices for the next year, presenting these results through interactive plots. This project is an end-to-end stock price prediction tool for analyzing trends and forecasting future prices using time-series modeling.

# FEATURES
This project offers a variety of features, including real-time stock data fetching, detailed stock analysis, and future price prediction. It supports visualization of historical stock performance through candlestick charts, closing prices, and trading volumes. Additionally, it computes key technical indicators like RSI, MACD, Bollinger Bands, and Moving Averages for detailed trend analysis. The core predictive functionality utilizes LSTM, GRU, and ConvLSTM models to forecast stock prices for the upcoming year. Each model's prediction is visualized through interactive Plotly graphs, offering users intuitive insights into future price trends. The project also provides a user-friendly interface, facilitating easier interpretation of the analysis and prediction results.

# KEY TECHNOLOGIES
This project employs a diverse set of technologies, starting with Python for all data handling, machine learning, and visualization tasks. For data analysis and manipulation, the project relies on libraries such as Pandas and NumPy, while visualizations are crafted using Matplotlib, Seaborn, and Plotly. Stock data is fetched in real time using the yFinance API. Machine learning models are built and trained using TensorFlow and Keras frameworks, with Scikit-learn employed for data preprocessing and evaluation metrics. For future extensions, the project is designed to integrate Flask for backend support, enabling web-based interactions and user inputs.

# USAGE
The project offers an intuitive workflow for stock price analysis and prediction. First, real-time stock data is fetched for the selected companies, including major tech giants like Apple, Google, Microsoft, and Amazon. This data is then processed and visualized, providing insights into historical trends, closing prices, and trading volumes. Additionally, various technical indicators such as RSI and MACD are computed and visualized. For forecasting, LSTM, GRU, and ConvLSTM models are applied to predict future stock prices, with the results visualized in comprehensive and interactive graphs. Users can easily navigate through the project to gain insights into both historical and future stock price trends.

# TECHNICAL INDICATORS USED
This project incorporates several technical indicators to help users better understand stock price movements and market trends. The Relative Strength Index (RSI) measures the speed and change of price movements to identify overbought or oversold conditions in the market. The Moving Average Convergence Divergence (MACD) helps analyze the relationship between short-term and long-term price trends through moving averages. Bollinger Bands are used to track volatility by setting price channels around a stock's moving average, providing insights into potential overbuying or overselling conditions. Lastly, the project incorporates Moving Averages (MA), including 20-day, 50-day, and 200-day averages, to smooth out fluctuations in stock prices and identify long-term trends.

# FUTURE ENHANCEMENTS
The project has several future enhancements planned. One major extension involves developing a fully interactive web-based user interface using Flask and Plotly Dash. This will allow users to interact with stock data and predictions in real time, improving the overall user experience. Additionally, performance optimizations will be implemented to reduce the time taken for model predictions and improve the accuracy of forecasts. New features, such as the ability to download reports and customized user analytics, will also be incorporated to make the project more user-friendly and functional.
