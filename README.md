# Login-Page
This is a Simple login page created with the node.js
# 🛡️ Express Login System with Sessions

This project is a simple login system built with **Node.js**, **Express**, and **Handlebars (HBS)**. It uses **express-session** for session management and demonstrates basic login/logout functionality with session-based access control.

---

## 🚀 Features

- Simple login form with session authentication
- Express.js as backend server
- Handlebars (HBS) templating engine
- Session handling with `express-session`
- No-cache middleware for better session control
- Static file serving using the `public/` folder

---

## 🧱 Tech Stack

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Handlebars](https://handlebarsjs.com/)
- [express-session](https://www.npmjs.com/package/express-session)
- [nocache](https://www.npmjs.com/package/nocache)

---

## 📁 Project Structure

project/
├── public/ # Static files (CSS, JS, images)
├── views/ # HBS templates
│ ├── login.hbs
│ └── home.hbs
├── server.js # Entry point for Express server
├── package.json
└── package-lock.json


---

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

npm install

node server.js

http://localhost:3003/


🔐 Default Credentials
Username: admin

Password: admin@123

📌 Notes
Make sure views/login.hbs and views/home.hbs exist before running.

Static files go into the public/ folder.

This is a demonstration project; not intended for production use without enhancements like hashing passwords, using databases, etc.
