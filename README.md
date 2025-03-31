# Stock Web App

A modern web application to track your portfolio with real-time market data, manage holdings and much more.

## Key Features  

📊 **Portfolio Dashboard**  
- Real-time valuation of your holdings  
- Performance metrics and allocation breakdown  

💹 **Trade Execution**  (Beta Features Might Not Work Perfectly)
- Buy/sell stocks with simulated transactions  
- Trade confirmation and execution records  

🔍 **Market Data**  
- Real-time stock quotes and charts   

## Technology Stack  

**Backend**  
- Python 3 with Flask framework  
- SQLite database with CS50 library  
- Yahoo Finance API integration  
- Werkzeug security utilities  

**Frontend**  
- Responsive Bootstrap 5 design  
- Interactive charts with Chart.js  
- Client-side form validation  

**DevOps**  
- Pipenv for dependency management  
- Environment variable configuration  
- SQL database migrations  

## Quick Start Guide  

1. **Setup Environment**  
```bash
git clone https://github.com/yourusername/stock-portfolio-tracker.git
cd stock-portfolio-tracker
pipenv install
pipenv shell
```

2. **Configure Application**  
```bash
cp .env.example .env
# Edit .env with your API keys and configuration
```

3. **Initialize Database**  
```bash
flask db upgrade
```

4. **Launch Application**  
```bash
flask run
```

5. **Access Application**  
Open `http://localhost:5000` in your browser  

## Support  
For issues or feature requests, please open an issue on our [GitHub repository](https://github.com/yourusername/stock-portfolio-tracker/issues).  

*Note: This application uses simulated trading and market data for educational purposes only.*
*Also it might have some bugs*
