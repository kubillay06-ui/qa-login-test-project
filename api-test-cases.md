# API Test Cases — Login

## Test Case 1 — Valid Login
**Request:**
POST https://reqres.in/api/login
Body: { "email": "eve.holt@reqres.in", "password": "cityslicka" }

**Expected Result:**
- Status 200 OK
- Response includes token field

---

## Test Case 2 — Invalid Login (Missing Password)
**Request:**
POST https://reqres.in/api/login
Body: { "email": "eve.holt@reqres.in" }

**Expected Result:**
- Status 400 Bad Request
- Response includes error message
