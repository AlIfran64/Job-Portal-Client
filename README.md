# CareerCode - A Job Portal Websit
CareerCode is a full-stack web application that empowers users to build their professional portfolios, access career-prep resources, and manage job-related content seamlessly. Designed with scalability and user experience in mind, CareerCode integrates secure authentication, clean UI design, and robust backend functionality.

---

## 🔗 Live Site

- 🌐 [https://career-code-694c4.web.app](https://career-code-694c4.web.app)

---

## Features


- **Secure Authentication (Firebase)**  
  Auth system for login/register with protected routes to ensure user privacy.

- **Full CRUD via REST API**  
  Users can perform Create, Read, Update, and Delete operations on their portfolio data.

- **Cloud Storage with MongoDB Atlas**  
  All user data is stored in a scalable and secure NoSQL database.

---

## 🔗 Additional Links

- Server-side Repository: [https://github.com/AlIfran64/Job-Portal-Server](https://github.com/AlIfran64/Job-Portal-Server)

---

## Tech Stack

### Frontend
- [React.js](https://reactjs.org/) – Component-based UI
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework
- [Firebase Authentication](https://firebase.google.com/products/auth) - Authentication and hosting

### Backend
- [Node.js](https://nodejs.org/) – Server-side JavaScript runtime
- [Express.js](https://expressjs.com/) – Web framework for APIs
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) – Cloud-hosted NoSQL DB
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) – Secure token generation for user sessions


---

## Installation & Setup

> Make sure you have **Node.js**, **npm**, and **MongoDB Atlas** credentials ready.

---

### Frontend Setup

```bash
cd client
npm install
npm run dev
```
---

### Backend Setup

```bash
cd server
npm install
nodemon index.js
```
