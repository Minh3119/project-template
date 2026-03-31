# {{ cookiecutter.project_name }}

## 🚀 Overview
This Flask project was generated using a professional template with Application Factory pattern and Blueprints architecture.

## 🛠 Installation

### 1. Prerequisite
Ensure you have **Python {{ cookiecutter.python_version }}** or higher installed.

### 2. Quick Start
Simply run the batch script:
```
run.bat
```
This will automatically:
- Create virtual environment (`.venv`)
- Install dependencies
- Start the Flask development server

### 3. Manual Setup (Alternative)
Step 1: Create a virtual environment
```
python -m venv .venv
```

Step 2: Activate the environment
```
# On Windows:
.venv\Scripts\activate
# On macOS/Linux:
source .venv/bin/activate
```

Step 3: Install dependencies
```
pip install -r requirements.txt
```

Step 4: Run the application
```
python app.py
```

## 💻 Development

### Running the Application
```
python app.py
```
The application will be available at `http://127.0.0.1:5000`

### Environment Configuration
Copy `.env.example` to `.env` and modify as needed:
```
FLASK_ENV=development
FLASK_DEBUG=True
SECRET_KEY=your-secret-key
```

## 📁 Project Structure
- `app/`: Main application package (routes, models, templates, static)
- `config.py`: Configuration for different environments
- `app.py`: Application entry point
- `.env.example`: Environment variables template

## 🌐 Available Routes
- `/` - Home page
- `/about` - About page
- `/users` - Users listing
- `/posts` - Posts listing
- `/contact` - Contact form
- `/api/users` - Users API endpoint
- `/api/posts` - Posts API endpoint

---
**Version**: {{ cookiecutter.version }}
