# Login Test Cases

## Test Case 1 — Valid Login
**Steps:**
1. Go to login page
2. Enter valid username
3. Enter valid password
4. Click login

**Test Data:**
- Username: student
- Password: Password123

**Expected Result:**
User should login successfully and redirect to dashboard

---

## Test Case 2 — Invalid Password
**Steps:**
1. Enter valid username
2. Enter wrong password
3. Click login

**Expected Result:**
Error message should be displayed

---

## Test Case 3 — Invalid Username
**Steps:**
1. Enter wrong username
2. Enter valid password
3. Click login

**Expected Result:**
Error message should be displayed

---

## Test Case 4 — Empty Fields
**Steps:**
1. Leave username and password empty
2. Click login

**Expected Result:**
Warning message should appear

---

## Test Case 5 — Empty Password
**Steps:**
1. Enter valid username
2. Leave password empty
3. Click login

**Expected Result:**
Warning message should appear

---

## Test Case 6 — Empty Username
**Steps:**
1. Leave username empty
2. Enter valid password
3. Click login

**Expected Result:**
Warning message should appear

---

## Test Case 7 — Case Sensitivity Test
**Steps:**
1. Enter username as "Student"
2. Enter password as "password123"
3. Click login

**Expected Result:**
Login should fail if system is case-sensitive

---

## Test Case 8 — Long Input Test
**Steps:**
1. Enter very long username (100+ characters)
2. Enter very long password
3. Click login

**Expected Result:**
System should handle input properly without crashing

---

## Test Case 9 — Special Characters Test
**Steps:**
1. Enter special characters in username (e.g. @#$%)
2. Enter special characters in password
3. Click login

**Expected Result:**
System should validate input and show error message
