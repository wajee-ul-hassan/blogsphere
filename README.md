# 📝 BlogSphere

**BlogSphere** is a personal blogging platform built with the **MERN Stack** (MongoDB, Express.js, React, Node.js) and **Redux Toolkit**. It includes a rich text editor for creating and managing blog posts, supports dark/light themes, and uses **SendInBlue** for email-based subscriptions, contact, and comments. Only admin login is allowed for managing content.

---

## 🔧 Tech Stack

### Frontend

* React
* React Router
* Redux Toolkit
* CSS
* React Draft WYSIWYG Editor

### Backend

* Node.js
* Express.js
* MongoDB

### Email Service

* SendInBlue (for subscription, contact, and comments)

---

## ✨ Features

* Rich Text Editor for writing and editing blog posts
* Admin-only login for secure content management
* Dark and Light theme support
* Newsletter subscription with double opt-in via SendInBlue
* Contact and comment forms integrated with SendInBlue

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/blogsphere.git
cd blogsphere
```

### 2. Install Dependencies

```bash
# Backend dependencies
npm install

# Move to frontend
cd frontend
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root and add the following:

```env
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
SENDINBLUE_API_KEY=your_sendinblue_api_key
```

---

## 📦 Scripts

### Backend

```bash
npm run dev     # Run backend in development
npm start       # Run backend in production
```

### Frontend

```bash
cd frontend
npm start       # Start React frontend
```

---


