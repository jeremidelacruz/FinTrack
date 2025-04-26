# FinTracker - Personal Finance Tracker

FinTracker is a comprehensive personal finance management application that helps users track expenses, monitor income, analyze spending patterns, and manage their financial goals all in one place.

## Features

- **Dashboard:** Get a quick overview of your financial situation with key metrics.
- **Transaction Management:** Add, edit, and categorize your income and expenses.
- **Reports & Analytics:** Visualize your spending patterns with interactive charts.
- **Card Management:** Keep track of your credit cards and their balances.
- **Budget Planning:** Set up budgets for different expense categories.
- **User Authentication:** Secure login and registration system.

## Tech Stack

- **Backend:** Flask (Python web framework)
- **Database:** SQLAlchemy with SQLite
- **Frontend:** HTML, CSS, JavaScript
- **Authentication:** Flask-Login
- **Data Visualization:** Chart.js

## Installation and Setup

1. Clone the repository:
```
git clone https://github.com/yourusername/fintracker.git
cd fintracker
```

2. Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```
pip install -r requirements.txt
```

4. Run the application:
```
python app.py
```

5. Access the application at `http://localhost:5000`

## Project Structure

```
fintracker/
├── app.py                  # Main application file
├── requirements.txt        # Project dependencies
├── static/                 # Static files (CSS, JS)
│   └── css/                
│       └── fintracker.css  # Main stylesheet
├── templates/              # HTML templates
│   ├── base.html           # Base template
│   ├── login.html          # Login page
│   ├── register.html       # Registration page
│   ├── dashboard.html      # Dashboard page
│   ├── transactions.html   # Transactions page
│   ├── reports.html        # Reports page
│   └── cards.html          # Cards page
└── README.md               # Project documentation
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Icon and design inspiration: [Lucide Icons](https://lucide.dev/)
- Chart library: [Chart.js](https://www.chartjs.org/)

