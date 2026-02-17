test-cases/api-test-cases.md
# API Test Cases — Sample Project

## Endpoint
GET /users/{id}

### Test Case 1 — Valid ID
Expected Result:
200 OK  
User object returned  

---

### Test Case 2 — Invalid ID
Expected Result:
404 Not Found  

---

### Test Case 3 — Missing Authorization
Expected Result:
401 Unauthorized  

---

### Test Case 4 — SQL Injection Attempt
Input:
?id=1 OR 1=1

Expected Result:
400 Bad Request or sanitized response
