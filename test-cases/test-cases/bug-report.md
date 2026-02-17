# Bug Report — Sample Issue

## Bug ID
BR-001

## Title
User endpoint returns 500 error for valid ID

## Environment
API version: v1  
Environment: QA  
Method: GET  

## Endpoint
GET /users/123

## Steps to Reproduce
1. Send GET request to /users/123
2. Observe response

## Expected Result
200 OK  
User object returned

## Actual Result
500 Internal Server Error

## Severity
High

## Priority
High

## Notes
Issue may be related to database lookup failure or null pointer exception.
