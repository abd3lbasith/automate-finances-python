# Automate Finances with Python
A simple finance dashboard built with Python, Streamlit, and Plotly to categorize transactions, track expenses, and visualize spending.

## Features
- Upload a CSV bank statement
- Automatically categorize transactions using keywords
- Add and manage custom categories
- Edit and apply categories interactively
- View expenses summary and breakdown by category
- Visualize spending with charts
- Track payments and totals
- Save categories for future sessions

## Getting Started

### Prerequisites
- Python 3.10 or later

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/abd3lbasith/automate-finances-python.git
   cd automate-finances-python
2. Create and activate a virtual environment:
python3 -m venv .venv
source .venv/bin/activate   # macOS/Linux
# .venv\Scripts\activate    # Windows

3. Install dependencies:
pip install -r requirements.txt

4. Run the App
streamlit run main.py

## How It Works
Upload a CSV file with columns such as Date, Details, Amount, Debit/Credit.
Transactions are matched against keywords in categories.json.
Unmatched transactions can be assigned to new or existing categories.
Changes are saved so future uploads are categorized automatically.
