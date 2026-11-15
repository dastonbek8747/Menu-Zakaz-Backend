# Menu-Zakaz-Backend

Restoran menyusi va buyurtmalarini boshqaruvchi FastAPI backend.

## Imkoniyatlar

- Menyu va buyurtmalar uchun REST API
- PostgreSQL + SQLAlchemy
- Pydantic sxemalari

## O'rnatish

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Sozlash

`.env.example` dan nusxa olib `.env` yarating va `DATABASE_URL` ni to'ldiring:

```bash
cp .env.example .env
```

## Ishga tushirish

```bash
uvicorn main:app --reload
```

## Litsenziya

MIT
