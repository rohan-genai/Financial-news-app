# FinancePulse - Real-time Financial News Platform

![FinancePulse Demo](https://via.placeholder.com/800x400?text=FinancePulse+Demo)

## 📈 Overview

FinancePulse is a real-time financial news aggregator built with Flask and modern front-end technologies. The platform fetches the latest financial market news, stock trends, and market summaries to keep users informed about the financial world.

## ✨ Features

- **Real-time Financial News Feed**: Latest news articles from trusted financial sources
- **News Sidebar**: Compact view of additional news stories
- **Market Trends**: Track top gainers and losers in the stock market
- **Market Summary**: Quick overview of major market indices
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Search Functionality**: Find specific financial news and topics

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Python, Flask
- **API**: Alpha Vantage Financial News API

## 📋 Prerequisites

- Python 3.8+
- Alpha Vantage API key (get a free key at [Alpha Vantage](https://www.alphavantage.co/))

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/financepulse.git
   cd financepulse
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Create environment variables**
   
   Create a `.env` file in the project root with the following:
   ```
   ALPHA_VANTAGE_API_KEY=your_api_key_here
   ```

5. **Run the application**
   ```bash
   python app.py
   ```

6. **Access the website**
   
   Open your browser and navigate to `http://localhost:5000`

## 📁 Project Structure

```
financial-news-app/
├── app.py                # Flask application
├── .env                  # Environment variables (create this file)
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
├── static/
│   ├── css/
│   │   └── styles.css    # Application styling
│   └── js/
│       └── main.js       # Frontend JavaScript
└── templates/
    └── index.html        # Main HTML template
```

## 🔄 API Integration

This project uses the Alpha Vantage API to fetch financial data:

- **Financial News**: `/api/news` endpoint fetches the latest market news
- **Market Trends**: `/api/market_trends` endpoint retrieves top gainers and losers

## 🖼️ Screenshots

### Desktop View
![Desktop View](https://via.placeholder.com/800x600?text=Desktop+View)

### Mobile View
![Mobile View](https://via.placeholder.com/400x800?text=Mobile+View)

## 🧩 Future Enhancements

- User accounts with personalized news feeds
- Stock watchlist functionality
- Real-time price charts for selected stocks
- News notifications for important market events
- Advanced search filters and categories

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🙏 Acknowledgements

- [Alpha Vantage](https://www.alphavantage.co/) for providing financial data APIs
- [Font Awesome](https://fontawesome.com/) for the beautiful icons
- [Flask](https://flask.palletsprojects.com/) for the web framework
