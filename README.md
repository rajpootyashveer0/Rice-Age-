
# Rice Age

IoT Rice Quality and Age Analysis Portal.

## Project Overview

A centralized portal for receiving IoT rice analyzer data, monitoring rice quality, viewing rice age estimates, and analyzing scan history.

## Technology Stack

- Python
- FastAPI
- PostgreSQL (planned)
- HTML, CSS, JavaScript (planned)

## Project Structure

- backend/ - Backend application
- frontend/ - Frontend application
- docs/ - Project documentation
- scripts/ - Utility scripts

## Backend Setup

```powershell
cd backend
py -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Run Development Server

```powershell
python -m uvicorn app.main:app --reload
```

## API Documentation

http://127.0.0.1:8000/docs

## Health Endpoint

http://127.0.0.1:8000/api/v1/health
