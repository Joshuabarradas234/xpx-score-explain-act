```markdown
# XPX Score → Explain → Act

A full-stack demo that simulates a **salary advance risk scoring** workflow: submit an application, receive a **risk score**, get an **explanation of top drivers**, and a recommended **action** (Approve / Review / Decline).

Built with **FastAPI** (backend) and **Vite** (frontend).

> **LinkedIn-ready demo:** clear UI, explainability, and an API you can test via Swagger.



## Quick Demo Links (Local)
- **Frontend:** http://localhost:5173 (or 5174 if 5173 is busy)
- **Backend Swagger:** http://127.0.0.1:8000/docs
- **OpenAPI JSON:** http://127.0.0.1:8000/openapi.json



## What This Project Shows

This repo demonstrates a real-world decisioning pattern commonly used in fintech and credit systems:

1. **Score** – compute a risk score  
2. **Explain** – return the top drivers behind the decision  
3. **Act** – recommend an action and risk band (Green / Amber / Red)



## Key Features
- End-to-end flow: **request → score → explanation → action**
- Explainability via **top drivers**
- Policy reference included in responses
- API-first design with Swagger & OpenAPI
- Simple UI with raw JSON output for transparency



## Tech Stack

### Backend
- Python
- FastAPI
- Uvicorn
- Pydantic

### Frontend
- Vite
- JavaScript
- Fetch API



## Repository Structure

```

.
├── backend/
│   ├── app/
│   │   └── main.py
│   ├── requirements.txt
│   └── tests/
├── frontend/
│   ├── package.json
│   └── vite.config.js
├── docs/
│   └── screenshots/
└── README.md

````

## Screenshots

Save images in `docs/screenshots/` using the filenames below.

### Repository overview

![Repository overview](docs/screenshots/01-repo-overview.png)

### Backend running (terminal)

![Backend running](docs/screenshots/02-backend-running.png)

### Swagger API docs

![Swagger docs](docs/screenshots/03-swagger-docs.png)

### Swagger – Try it out

![Swagger try it out](docs/screenshots/04-swagger-try-it-out.png)

### Frontend running (terminal)

![Frontend running](docs/screenshots/05-frontend-running.png)

### Frontend UI – form input

![Frontend UI](docs/screenshots/06-frontend-ui.png)

### Result panel with explanation

![Result explanation](docs/screenshots/07-result-explanation.png)

### Raw JSON output

![Raw JSON](docs/screenshots/08-raw-json.png)



## Notes

* This project is for **demonstration and portfolio purposes only**
* Do **not** use real personal or financial data
* Scoring logic is illustrative, not production-grade



## License

MIT License

```
