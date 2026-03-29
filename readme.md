#  Sudoku Solver (Full Stack Project)

A full-stack Sudoku Solver web application built using **Spring Boot (Java)** for backend and **HTML, CSS, JavaScript** for frontend.

##  Live Demo

* Frontend: https://sudoku-frontend-sigma.vercel.app
* Backend API: https://sudoku-backend-production-4886.up.railway.app

---

##  Tech Stack

### Backend

* Java
* Spring Boot
* REST APIs
* Maven

### Frontend

* HTML
* CSS
* JavaScript (Fetch API)

### Deployment

* Backend: Railway
* Frontend: Vercel

---

##  Features

*  Solve any 9x9 Sudoku puzzle
*  Fast backtracking algorithm
*  Full-stack API integration
*  Clean UI with 3×3 grid separation
*  Handles empty cells (0 as blank)
*  Deployed and live

---

##  How It Works

1. User enters Sudoku values in grid
2. Frontend converts input → JSON
3. Sends POST request to backend `/solve`
4. Backend solves puzzle using recursion
5. Returns solved grid as JSON
6. Frontend displays result

---

##  API Endpoint

### POST /solve

Request:

```json
{
  "board": [[5,3,0,...],[...]]
}
```

Response:

```json
[[5,3,4,...],[...]]
```

---

##  Learning Outcomes

* REST API development using Spring Boot
* JSON ↔ Object conversion (Jackson)
* Frontend-backend integration
* Debugging real-world deployment issues
* Hosting on cloud platforms

---

##  Author

Lokesh Soni
Phone:  8595598458
Mail:  [mrlokeshsoni001@gmail.com](mailto:mrlokeshsoni001@gmail.com)

---

##  Future Improvements

* Input validation (invalid Sudoku detection)
* Step-by-step solving visualization
* Difficulty levels (Easy/Hard)
* User authentication

---
 This project demonstrates real-world full-stack development skills.
