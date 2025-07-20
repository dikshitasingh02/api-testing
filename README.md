# 🧪 API Testing with Postman

This project demonstrates manual API testing using [Postman](https://www.postman.com/) on the free public API — [JSONPlaceholder](https://jsonplaceholder.typicode.com/). It covers testing for all major HTTP methods: GET, POST, PUT, PATCH, and DELETE.

---
## 🔧 Tools & Technologies

- **Postman**: API testing tool
- **JSONPlaceholder**: Fake online REST API
- **Microsoft Excel**: For writing test cases
- **PDF Report**: For presenting results with screenshots

---

## 📌 APIs Tested

Base URL: `https://jsonplaceholder.typicode.com`

| Method | Endpoint             | Description                   |
|--------|----------------------|-------------------------------|
| GET    | `/posts`             | Fetch all posts               |
| GET    | `/posts/{id}`        | Fetch a post by ID            |
| POST   | `/posts`             | Create a new post             |
| PUT    | `/posts/{id}`        | Update a full post            |
| PATCH  | `/posts/{id}`        | Partially update a post       |
| DELETE | `/posts/{id}`        | Delete a post                 |

---

## ✅ Testing Focus

- **Status Code Validation** (200, 201, 204, 404, etc.)
- **Response Time Check**
- **Response Body Structure**
- **JSON Key Validation**

---

## 📋 Sample Test Case Format (Excel)

| Test Case ID | Method | Endpoint     | Expected Status | Validation Criteria        |
|--------------|--------|--------------|------------------|----------------------------|
| TC_001       | GET    | `/posts`     | 200              | Response contains JSON array of posts |
| TC_002       | POST   | `/posts`     | 201              | New post is returned with ID |

---

## 🖼️ Sample Screenshots

Check the `DummyScreenshots` folder for:
- Test setup in Postman
- Response preview
- Status code verification

---

## 📌 How to Use

1. Open [Postman](https://www.postman.com/downloads/).
2. Import the API endpoints from the documentation or manually enter them.
3. Use the Excel test case file to guide your testing.
4. Observe and validate responses.
5. Refer to the PDF report for visual representation and documentation.

---

## 👩‍💻 Author

**Dikshita Singh**  
GitHub: [@dikshitasingh02](https://github.com/dikshitasingh02)

---

## 📄 License

This project is for educational/demo purposes. You are free to use, modify, and share it.
