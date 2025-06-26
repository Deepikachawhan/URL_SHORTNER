# 🚀 URL Shortener Project 🔗

A full-stack URL Shortener application with user authentication, dashboard, and analytics. This project is divided into two main parts: **Backend** (Node.js/Express/MongoDB) and **Frontend** (React/Vite).

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js, MongoDB
- **Frontend:** React, Vite, Redux Toolkit

---

## ✨ Features
- 👤 User registration and login
- ✂️ Create, view, and manage short URLs
- 📉 Shorten URLs
- 🔁 Redirect shortened URLs to the original URLs
- 🔢 Track the number of visits for each URL
- 📊 User dashboard with analytics
- 📱 Responsive UI

---

## 📁 Project Structure

```
URL_SHORTNER/
├── BACKEND/
│   ├── app.js
│   ├── package.json
│   └── src/
│       ├── config/
│       ├── controller/
│       ├── dao/
│       ├── middleware/
│       ├── models/
│       ├── routes/
│       ├── services/
│       └── utils/
├── FRONTEND/
│   ├── index.html
│   ├── package.json
│   ├── vite.config.js
│   └── src/
│       ├── api/
│       ├── components/
│       ├── pages/
│       ├── routing/
│       ├── store/
│       └── utils/
```

---

## 🚦 Getting Started

### Backend
1. 📂 Navigate to `BACKEND/`
2. 📦 Install dependencies:
   ```sh
   npm install
   ```
3. 📝 Set up your `.env` file (see `config.js` for required variables)
4. ▶️ Start the server:
   ```sh
   npm start
   ```

### Frontend
1. 📂 Navigate to `FRONTEND/`
2. 📦 Install dependencies:
   ```sh
   npm install
   ```
3. ▶️ Start the development server:
   ```sh
   npm run dev
   ```

---

## 🌟 Conclusion

This project showcases a modern, full-stack approach to building scalable web applications. By combining a robust backend with a dynamic frontend, it delivers a seamless user experience for URL shortening and management. The modular structure and use of popular technologies make it easy to maintain and extend. Thank you for exploring this project! 🚀
