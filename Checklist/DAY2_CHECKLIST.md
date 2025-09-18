
# ✅ Day 2 – Budget App Journal Checklist

## 🎯 Goal for Day 2
Set up the **Backend MVP** with authentication and transaction handling.

---

## 🏗 Backend Development Tasks
- [ ] Create models with SQLAlchemy:
  - [ ] **User** (id, email, password_hash)
  - [ ] **Category** (id, name)
  - [ ] **Transaction** (id, user_id, amount, type, category_id, date, note)
- [ ] Set up database connection (`database.py`).
- [ ] Apply migrations or auto-create SQLite database.

---

## 🔑 Authentication
- [ ] Install and configure **Flask-JWT-Extended**.
- [ ] Create **signup endpoint** (`POST /auth/signup`).
- [ ] Create **login endpoint** (`POST /auth/login`).
- [ ] Return JWT token on successful login.

---

## 🔄 Transactions API
- [ ] Create endpoint: `GET /transactions` → fetch user’s transactions.
- [ ] Create endpoint: `POST /transactions` → add new income/expense.
- [ ] Ensure endpoints require JWT authentication.

---

## 📖 API Documentation
- [ ] Install **flasgger** (or FastAPI if switching).
- [ ] Add Swagger/OpenAPI docs for signup, login, and transactions.

---

## 🧪 Testing
- [ ] Use **Postman** to test signup/login.
- [ ] Confirm JWT token works for protected routes.
- [ ] Test creating a transaction and fetching it.

---

## 🗂 Documentation & Journal
- [ ] Update backend **README.md** with new endpoints.
- [ ] Journal entry: write what endpoints you created and tested, note any bugs.

---

👉 By the end of Day 2, you should have:
✔ User signup & login working with JWT.  
✔ Ability to add and view transactions (linked to user).  
✔ API documented (Swagger/OpenAPI).  
✔ Tested endpoints in Postman.  
