# 🚀 Crypto Price Tracker Using CoinMarketCap API

This project is a Jupyter Notebook-based solution to **track cryptocurrency prices and trends** in real-time using the CoinMarketCap API. It normalizes the data into Pandas DataFrames, allows analysis over different time frames, and visualizes trends using Seaborn and Matplotlib.

---

## **Features**

- 🔹 Fetch latest cryptocurrency listings using the **CoinMarketCap API**  
- 🔹 Normalize JSON data into **Pandas DataFrames** for easy manipulation  
- 🔹 Append new API data to existing DataFrames or CSV files  
- 🔹 Track historical trends for coins like Bitcoin over multiple time periods: 1h, 24h, 7d, 30d, 60d, 90d  
- 🔹 Visualize price and percent changes using **Seaborn** and **Matplotlib**  
- 🔹 Configurable to fetch **top N cryptocurrencies**  

---

## **Setup Instructions**

1. **Clone the Repository**  
2. **Create a Virtual Environment**  
3. **Install Dependencies**  
4. **Get CoinMarketCap API Key**  
5. **Set Up Environment Variables**  
6. **Launch Jupyter Notebook**  

> ⚠️ If you encounter data rate limit issues, adjust the notebook data rate limit settings.

---

## **How It Works**

- **API Request**: Fetches the latest cryptocurrency data from CoinMarketCap  
- **Data Normalization**: Converts JSON response into a Pandas DataFrame  
- **Data Storage**: Optionally append to a CSV file for historical tracking, with timestamps  
- **Data Analysis**: Groups coins by name and calculates percent changes over different time frames  
- **Visualization**: Generates point plots and line plots for trends using Seaborn and Matplotlib  

---

## **Sample Visualizations**

- **Coin Trends Over Time**: Compare percent change across 1h, 24h, 7d, 30d, 60d, and 90d to identify short-term vs long-term trends  
- **Bitcoin Price Over Time**: Line plot showing Bitcoin prices with timestamps; easily extendable to other coins  

---

## **Tips & Notes**

- Ensure the API key is valid and has sufficient quota  
- Use loops with sleep intervals for periodic API requests  
- Display all columns using Pandas display options  
- Format large numbers to avoid scientific notation  
- Backup CSV files if running API requests repeatedly  

---

## **Future Improvements**

- 🔹 Add support for dynamic cryptocurrency selection  
- 🔹 Include interactive dashboards using Streamlit or Plotly  
- 🔹 Incorporate alert system for price changes  
- 🔹 Enable comparison between multiple coins in the same visualization  

---

## **License**

This project is **open-source** and free to use for personal or educational purposes.  

---

 
