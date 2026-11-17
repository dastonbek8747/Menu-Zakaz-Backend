# FastAPI Menu & Order Backend

> A REST API for a restaurant menu and order service. Full CRUD for users, categories, dishes and orders, built with FastAPI and PostgreSQL.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)


## Features

- CRUD endpoints for users, categories, dishes and orders.
- SQLAlchemy models with foreign keys between orders, dishes and users.
- Pydantic schemas for request validation and response shaping.
- Auto-generated Swagger docs at `/docs`.

## Tech Stack

| Layer | Technology |
|---|---|
| API | FastAPI, Uvicorn |
| ORM | SQLAlchemy |
| Database | PostgreSQL |
| Validation | Pydantic |

## Quick Start

```bash
git clone https://github.com/dastonbek8747/fastapi-menu-order-backend.git
cd fastapi-menu-order-backend
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env      # set DATABASE_URL
uvicorn main:app --reload
```

Open http://localhost:8000/docs for the interactive API.

## Environment variables

| Variable | Meaning |
|---|---|
| `DATABASE_URL` | PostgreSQL connection string. |

## Project Structure

```
.
├── main.py          # FastAPI app and routes
├── models.py        # SQLAlchemy models
├── schemas.py       # Pydantic schemas
├── db_connect.py    # engine, session, Base
└── Images/          # sample dish images
```

## License

MIT © 2026 Doston Sultonov.
