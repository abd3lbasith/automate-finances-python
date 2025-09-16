## Automate Finances with Python
A lightweight finance dashboard built with Python, Streamlit, and Plotly to help you categorize transactions, track expenses, and visualize spending.
Live Demo: https://automate-finances-python-do3wzwk9krrfvwgz6ayxkz.streamlit.app

## Features
Upload CSV bank statements
Auto-categorize transactions using keywords
Add, edit, and manage custom categories
Save categories for future sessions
View expense summaries and category breakdowns
Interactive charts to visualize spending
Track payments and totals
## Getting Started
### Prerequisites
Python 3.10+
Installation
### Clone the repository:
git clone https://github.com/abd3lbasith/automate-finances-python.git
cd automate-finances-python
### Create and activate a virtual environment:
python3 -m venv .venv
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows
### Install dependencies:
pip install -r requirements.txt
### Run the app:
streamlit run main.py
## How It Works
Upload a CSV with columns like Date, Details, Amount, Debit/Credit.
Transactions are matched against keywords in categories.json.
Unmatched transactions can be manually assigned to categories.
Categories are saved for automatic use in future uploads.
