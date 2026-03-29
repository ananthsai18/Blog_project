# 📌 Full Stack Blog App (Image Upload)

## 🚀 Overview

This is a beginner full-stack blog application where users can create posts with an image and a caption, and view them in a feed.

The project was built while learning backend fundamentals, API creation, and frontend-backend integration.

---

## 🧠 What I Learned

### 🔹 Backend (Node.js + Express)

* Creating REST APIs
* Structuring backend project (routes, services, models) → I organized the backend into separate folders where routes handle incoming requests, services contain the main logic (like uploading images or saving data), and models define how data is stored in MongoDB. This helped me understand how real-world backend projects are structured.
* Connecting to MongoDB → I connected the backend to MongoDB using a connection string and learned how to store and retrieve blog data using schemas and models.
* Handling file uploads using Multer → I used Multer middleware to accept image files from the frontend form and process them before sending them to the server.
* Uploading images to ImageKit → After receiving the file with Multer, I uploaded it to ImageKit using its SDK and stored the returned image URL in the database so it can be displayed later.
* Using environment variables securely (.env)
* Understanding middleware and request flow

---

### 🔹 Frontend (React)

* Creating components and pages
* Using React Router for navigation
* Managing state with useState and useEffect
* Making API calls using Axios
* Handling forms and file uploads in React

---

### 🔹 Full Stack Integration

* Connecting frontend and backend using APIs
* Handling CORS issues
* Sending form data (multipart/form-data)
* Displaying dynamic data from backend

---

## 🛠 Tech Stack

### Frontend

* React
* Axios
* React Router

### Backend

* Node.js
* Express.js
* MongoDB
* Multer
* ImageKit

---

## ⚙️ Features

* 📤 Create post with image upload
* 🖼 Store images using ImageKit
* 📝 Add caption to posts
* 📃 View all posts in feed

---

## 📁 Project Structure

```bash
Blog_Project/
 ├── Backend/
 │   ├── src/
 │   │   ├── db/
 │   │   ├── models/
 │   │   ├── services/
 │   │   └── app.js
 │   └── server.js
 │
 ├── Frontend/
 │   ├── src/
 │   │   ├── pages/
 │   │   └── App.jsx
 │
 └── README.md
```

---

## 🔐 Environment Variables

Create a `.env` file in the backend folder:

```env
IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=your_url_endpoint
MONGO_URI=your_mongodb_connection
```

---

## ▶️ How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Blog_project.git
```

---

### 2️⃣ Backend setup

```bash
cd Backend
npm install
npm start
```

---

### 3️⃣ Frontend setup

```bash
cd Frontend
npm install
npm run dev
```

---

## ⚠️ Limitations (Honest Note)

* Basic UI (focus was on functionality)
* No authentication system
* Minimal error handling
* Not deployed yet

---

## 🎯 Future Improvements

* Add authentication (login/signup)
* Improve UI/UX
* Add loading states
* Add delete/edit post feature
* Deploy frontend and backend

---

## 💡 Conclusion

This project helped me understand how a full-stack application works end-to-end — from handling file uploads in the backend to displaying data dynamically in the frontend.


It marks my transition from learning individual technologies to building complete applications.
------------------------------------------------------------------------------------------------------------
<img width="718" height="682" alt="Screenshot 2026-03-29 173410" src="https://github.com/user-attachments/assets/23db9264-e995-496d-a2e9-5b29491e98ad" />
<img width="1920" height="1080" alt="Screenshot (146)" src="https://github.com/user-attachments/assets/43b65f4e-09f5-49dc-beb6-c9e1fdc62b04" />



