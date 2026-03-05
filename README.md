# API Testing with Postman

REST API testing project using Postman, including automated tests and Newman CLI reports.

---

## Tools Used

- Postman
- Newman CLI
- JavaScript (Postman test scripts)

---

## What Is Tested

The following aspects of the API are validated:

- HTTP status codes
- Response structure
- Response data values

Example test validation:

```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
