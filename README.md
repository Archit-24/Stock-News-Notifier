# Stock News Notifier

This Python project serves as a stock news notifier, allowing users to track the price of a desired stock. Users can specify the stock they want to monitor and set a target price. When the stock price hits the target value, the program automatically sends a mobile message notification to the user. It leverages stock data APIs for retrieving real-time stock prices and messaging services for sending notifications.

## Features

- **Stock Price Tracking**: Tracks the price of a specified stock in real-time.
- **Custom Price Alert**: Allows users to set their desired price for the stock.
- **Real-time Notifications**: Sends mobile message notifications to the user when the stock price hits the desired value.
- **Stock Data APIs**: Utilizes stock data APIs (e.g., Alpha Vantage, Yahoo Finance) for retrieving real-time stock prices.
- **Messaging Service Integration**: Integrates with messaging services (e.g., Twilio) for sending mobile message notifications.
- **Error Handling**: Handles errors gracefully and provides informative error messages.

## Technologies Used

- **Python Libraries**:
  - `requests` for making HTTP requests to stock data APIs
  - `Twilio` or similar libraries for sending mobile message notifications
- **Stock Data APIs**: Utilizes stock data APIs such as Alpha Vantage, Yahoo Finance, or similar services for retrieving real-time stock prices.
- **Messaging Service**: Integrates with messaging services like Twilio for sending mobile message notifications.

## Installation

1. Clone the repository: `git clone https://github.com/yourusername/stock-news-notifier.git`
2. Navigate to the project directory: `cd stock-news-notifier`
3. Install dependencies: `pip install -r requirements.txt`
4. Sign up for a developer account with a stock data API provider (e.g., Alpha Vantage) and obtain an API key.
5. Sign up for a messaging service provider (e.g., Twilio) and obtain credentials for sending mobile messages.

## Usage

1. Configure the stock data API key and messaging service credentials in the appropriate configuration file or environment variables.
2. Run the main Python script: `python main.py`.
3. Follow the prompts to enter the stock symbol you want to monitor and set the target price.
4. The program will continuously monitor the stock price and send a mobile message notification when the stock price hits the target value.
5. Optionally, configure additional settings such as the frequency of price checks or specific stock exchanges to track.
