# Currency Converter

A simple **Currency Converter** app built with **React** that fetches real-time currency exchange rates using a **real-time currency API**. This app allows users to convert between various currencies and provides an easy-to-use interface for currency conversion.

## Features

- 💱 **Real-time currency conversion** based on the latest exchange rates.
- 🌍 **Supports multiple currencies** (USD, EUR, INR, GBP, etc.).
- 🔄 **Swap functionality** to quickly switch between currencies.
- 📱 **Responsive design** optimized for both desktop and mobile.
- ⚛️ Built with **React** and styled using **Tailwind CSS**.

## Technologies Used

- **React** - Frontend JavaScript library.
- **Tailwind CSS** - Utility-first CSS framework for styling.
- **Axios** - For making API requests to get live currency exchange rates.
- **Real-time Currency API** - Provides the exchange rates (e.g. [ExchangeRate-API](https://www.exchangerate-api.com/), [CurrencyLayer](https://currencylayer.com/)).

## 🚀 Live Preview

Check out the live version of the app here:  
🔗 (https://currency-convertor-rouge-rho.vercel.app/)

## 🛠️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/Praneeth76/currency-convertor.git
cd currency-convertor
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up your API key
Create a .env file in the root directory and add your API key like this:
```
REACT_APP_API_KEY=your_api_key_here
Replace your_api_key_here with your actual key from the currency exchange API provider.
```

### 4. Start the development server
```
npm start
```
Your app will be available at http://localhost:3000.

## 📄 License
This project is open source and available under the MIT License.
