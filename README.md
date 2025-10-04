# 🚀 WanderNest — MERN Travel Web App

✈️ **WanderNest** is a full-featured travel booking and exploration web app built with **Node.js, Express.js, MongoDB, EJS, and Cloudinary**. It features a dynamic UI, authentication, cloud image uploads, and follows an **MVC architecture**.

## 🔥 Features

* 🔐 **Secure user authentication** with Passport.js
* 🧾 **Form validation** using Joi
* ☁️ **Cloud image uploads** via Cloudinary
* 💬 **Flash messages** for real-time UI feedback
* 📦 **Modular MVC architecture**: Controllers, Models, Routes, Views
* 🌍 **Dynamic pages rendered with EJS**
* ⚙️ **Deploy-ready** with Netlify and `serverless-http`

---

## 📁 Project Structure

```
WanderNest/
│
├── controllers/       # Logic for each route
├── models/            # Mongoose schemas
├── routes/            # Express route files
├── views/             # EJS templates
├── public/            # Static assets (CSS, JS, images)
├── utils/             # Helper functions
│
├── app.js             # Main Express server
├── cloudConfig.js     # Cloudinary setup
├── middleware.js      # Auth & error handlers
├── schema.js          # Joi validation schemas
├── netlify.toml       # Netlify config
├── .env               # Environment variables
└── README.md          # Project documentation
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repo

```bash
git clone https://github.com/supriya0415/Major-project
cd Major-Project
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Setup environment variables

Create a `.env` file in the root folder:

```
DB_URL=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_KEY=your_api_key
CLOUDINARY_SECRET=your_api_secret
SESSION_SECRET=your_custom_secret
```

### 4️⃣ Start the development server

```bash
npm start
```

Go to 👉 [http://localhost:3000](http://localhost:3000)

## 🖼️ Screenshots

> Place these images in the `/screenshots` folder for reference

* **Home Page**
* **Dashboard Page**

## 🧠 Concepts You'll Learn

* MVC pattern with Express.js
* EJS templating engine
* Passport.js authentication
* MongoDB with Mongoose ORM
* Cloudinary integration for image uploads
* Flash messaging system
* Middleware-based validation (Joi)
* RESTful routing and modular project structure

🤝 Contribution

Contributions, issues, and feature requests are welcome!
Fork the project
Create your feature branch (git checkout -b feature/YourFeature)
Commit your changes (git commit -m 'Add some feature')
Push to the branch (git push origin feature/YourFeature)
Open a Pull Request
