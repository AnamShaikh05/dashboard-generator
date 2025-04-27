# Automated Dashboard Generator

A web-based application that allows users to upload Excel or CSV files and automatically generate interactive dashboards without requiring manual effort or external tools.

## Features

- **User Authentication**: Register, login, and manage your dashboards securely
- **File Upload**: Support for Excel (.xlsx, .xls) and CSV (.csv) files
- **Multiple Chart Types**: Bar charts, line charts, pie charts, and many more
- **Data Filtering**: Apply filters to focus on specific data segments
- **Dashboard Customization**: Choose themes and colors for better visualization
- **Export Options**: Save dashboards as PNG or PDF

## Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/dashboard-generator.git
cd dashboard-generator
```

2. Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```
pip install -r requirements.txt
```

4. Run the application:
```
python app.py
```

5. Open your browser and navigate to `http://127.0.0.1:5000/`

## Usage

1. Register a new account or login with existing credentials
2. Upload your Excel or CSV file
3. Configure your dashboard by selecting chart types and data fields
4. Preview and save your dashboard
5. Access your saved dashboards anytime from the dashboard list

## Project Structure

- `app.py`: Main Flask application
- `templates/`: HTML templates for the web pages
- `static/`: CSS styles and JavaScript files
- `uploads/`: Directory for uploaded files
- `dashboard.db`: SQLite database for user and dashboard data

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Data Processing**: Pandas
- **Visualization**: Plotly.js
- **Database**: SQLite

## License

This project is licensed under the MIT License - see the LICENSE file for details.