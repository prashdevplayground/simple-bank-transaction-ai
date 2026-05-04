# Bank Multi-Agent System

## Run Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

## Run with Docker
docker-compose up --build

## Frontend
Open frontend/index.html


# PROJECT STRUCTURE
bank-multi-agent/
│
├── backend/
│   ├── main.py
│   ├── agents/
│   │   ├── root_agent.py
│   │   ├── validation_agent.py
│   │   ├── fraud_agent.py
│   │   ├── transaction_agent.py
│   │   └── notification_agent.py
│   ├── db/
│   │   └── database.py
│   ├── models.py
│   └── requirements.txt
│
├── frontend/
│   ├── index.html
│   └── script.js
│
├── Dockerfile
├── docker-compose.yml
└── README.md
