# Project-DBMS

A Flask-based web application with MySQL database integration.

## Features

- User authentication and authorization
- MySQL database integration
- RESTful API endpoints
- Modern and responsive UI

## Prerequisites

- Python 3.8 or higher
- MySQL Server
- Git

## Local Development Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Project-DBMS.git
cd Project-DBMS
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory with the following variables:
```
DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_NAME=your_database_name
SECRET_KEY=your_secret_key
```

5. Initialize the database:
```bash
python init_db.py
```

6. Run the development server:
```bash
python app.py
```

The application will be available at `http://localhost:5000`

## Deployment

### Option 1: Deploy to Heroku

1. Create a Heroku account and install the Heroku CLI
2. Login to Heroku:
```bash
heroku login
```

3. Create a new Heroku app:
```bash
heroku create your-app-name
```

4. Add MySQL addon:
```bash
heroku addons:create jawsdb:kitefin
```

5. Set environment variables:
```bash
heroku config:set SECRET_KEY=your_secret_key
```

6. Deploy:
```bash
git push heroku main
```

### Option 2: Deploy to Python Anywhere

1. Create a Python Anywhere account
2. Upload your code using Git or the Python Anywhere file manager
3. Create a virtual environment and install dependencies
4. Configure your web app to use the virtual environment
5. Set up your MySQL database
6. Configure environment variables
7. Reload your web app

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details. #   P r o j e c t - D B M S  
 