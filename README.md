# 🍽 Menu Zakaz Backend (FastAPI)

Restoran menyusi va buyurtmalarni boshqarish uchun **FastAPI** backend. Menyu, buyurtma va foydalanuvchilarni REST API orqali boshqaradi.

---

## ✨ Imkoniyatlar

- 🍲 **Menyu boshqaruvi:** taomlar ro'yxati, tafsilotlar
- 🧾 **Buyurtmalar:** buyurtma yaratish va kuzatish
- 👤 **Foydalanuvchilar:** ro'yxatdan o'tish
- 🔌 **REST API:** to'liq CRUD endpointlari
- 📚 **Avtomatik hujjat:** Swagger UI (`/docs`)

---

## 🛠 Texnologiyalar

| Texnologiya | Maqsad |
|---|---|
| **Python 3.10+** | Asosiy til |
| **FastAPI** | REST API |
| **SQLAlchemy** | ORM |
| **Pydantic** | Sxemalar |
| **Uvicorn** | ASGI server |

---

## ⚙️ O'rnatish

```bash
git clone https://github.com/dastonbek8747/Menu-Zakaz-Backend.git
cd Menu-Zakaz-Backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

`.env` fayl yarating:

```env
DATABASE_URL=postgresql://user:pass@localhost/db
```

> 🔒 `.env` git'ga qo'shilmaydi.

---

## ▶️ Ishga tushirish

```bash
python main.py
# yoki: uvicorn main:app --reload
```

API hujjati: `http://localhost:8000/docs`

---

## 📁 Loyiha tuzilishi

```
Menu-Zakaz-Backend/
├── main.py           # FastAPI app va endpointlar
├── models.py         # SQLAlchemy modellari
├── schemas.py        # Pydantic sxemalari
├── db_connect.py     # Ma'lumotlar bazasi ulanishi
├── app.py
├── requirements.txt
└── Images/
```

---

## 📄 Litsenziya

Litsenziya ko'rsatilmagan.
