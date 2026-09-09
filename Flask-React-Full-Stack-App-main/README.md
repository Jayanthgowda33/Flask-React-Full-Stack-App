# Flask-React Full Stack App

A full-stack web application built with a **Flask** backend (REST API) and a **React** frontend. This project follows [techwithtim's](https://github.com/techwithtim) tutorial series and demonstrates how to connect a Python backend with a modern JavaScript frontend.

## Tech Stack

**Backend**
- Python
- Flask
- Flask-SQLAlchemy (if using a database)

**Frontend**
- React
- JavaScript

## Project Structure

Flask-React-Full-Stack-App/
├── backend/
│ ├── app.py
│ ├── config.py
│ ├── requirements.txt
│ └── ...
├── frontend/
│ ├── src/
│ ├── package.json
│ └── ...
└── README.md


## Getting Started

### Prerequisites
- Python 3.x installed
- Node.js and npm installed

### 1. Clone the repository
```bash
git clone https://github.com/Jayanthgowda33/Flask-React-Full-Stack-App.git
cd Flask-React-Full-Stack-App
```

### 2. Set up the backend
```bash
cd backend
python -m venv venv
venv\Scripts\activate      # Windows
# source venv/bin/activate  # Mac/Linux
pip install -r requirements.txt
python app.py
```
The backend will run at `http://localhost:5000` (default Flask port).

### 3. Set up the frontend
Open a new terminal:
```bash
cd frontend
npm install
npm start
```
The frontend will run at `http://localhost:3000` and communicate with the Flask backend.

## Environment Variables

If the backend requires configuration (e.g. `SECRET_KEY`, database URL), create a `.env` file inside `backend/` and add the required variables as specified in `config.py`.

## License

This project is for educational purposes, based on techwithtim's tutorial.
