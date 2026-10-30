# Django_Visualisation

A Django application for data visualization using Chart.js.

## Getting Started

### 1. Create and activate a virtual environment
```bash
python -m venv env
# On Windows:
.\env\Scripts\activate
# On Linux/macOS:
source env/bin/activate
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run migrations and load sample data
```bash
python manage.py migrate
python manage.py loaddata dashboard_data.json
```

### 4. Start the server
```bash
python manage.py runserver
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.
