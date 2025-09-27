# Flask REST API - User Management

## 📌 Objective
Create a REST API with Flask to manage user data (CRUD operations).

---

## 🚀 Setup

`bash
git clone <your-repo-link>
cd flask_rest_api_task
pip install -r requirements.txt
python app.py


Server will run at: http://127.0.0.1:5000/

🔑 Endpoints
1. Get all users

GET /users

2. Get user by ID

GET /users/<id>

3. Add new user

POST /users

{
  "name": "Bot",
  "email": "bot@example.com"
}

4. Update user

PUT /users/<id>

{
  "name": "Bot Updated",
  "email": "bot.new@example.com"
}

5. Delete user

DELETE /users/<id>

