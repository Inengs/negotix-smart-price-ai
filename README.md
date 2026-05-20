# SmartPrice AI

> Smart pricing for every hustle — a hackathon project

## Team

| Name             | Role                  |
| ---------------- | --------------------- |
| Emmanuel (Grizz) | Backend Lead + DevOps |
| Sibanda          | AI / Algorithms       |
| Karushna         | Frontend Lead         |

## Running locally

### Backend

```bash
cd backend
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
# → http://localhost:8000
```

### Frontend

```bash
cd frontend
npm install
npm run dev
# → http://localhost:5173
```

## API contract

See [docs/api-contract.md](docs/api-contract.md)
