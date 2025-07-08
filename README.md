# 🧭 WanderLust – Discover & Share Unique Stays

**WanderLust** is a sleek and user-friendly web platform that helps travelers discover unique short-term stays and share their experiences through property reviews. Built with the MERN stack (minus React 😉), it’s the perfect place to list your property or explore cozy getaways.

---

## 📖 Overview

WanderLust lets users:

- 🏡 **Explore Listings** – Discover a variety of short-term rental properties  
- 📝 **Write Reviews** – Share your stay experience on any listing  
- 👤 **Host Properties** – Add, edit, and manage listings 
- 🔐 **Sign Up/Login** – Secure user authentication and session management  
- 📱 **Enjoy Responsiveness** – Designed to look great on all screen sizes

---

## 📂 Folder Structure

WanderLust/
├── controllers/
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
├── init/
│   ├── data.js
│   └── index.js
├── listing_images/
├── models/
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── public/
│   ├── css/
│   │   ├── rating.css
│   │   └── style.css
│   └── js/
│       ├── map.js
│       └── script.js
├── routes/
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── utils/
│   ├── ExpressError.js
│   └── wrapAsync.js
├── views/
│   ├── includes/
│   │   ├── flash.ejs
│   │   ├── footer.ejs
│   │   └── navbar.ejs
│   ├── layouts/
│   │   └── boilerplate.ejs
│   ├── listings/
│   │   ├── edit.ejs
│   │   ├── filters.ejs
│   │   ├── index.ejs
│   │   ├── new.ejs
│   │   ├── result.ejs
│   │   └── show.ejs
│   ├── users/
│   │   ├── login.ejs
│   │   └── signup.ejs
│   └── error.ejs
├── .gitignore
├── app.js
├── cloudConfig.js
├── middleware.js
├── package-lock.json
├── package.json
└── schema.js

---

## 🛠️ Built With

- **Node.js & Express** – Backend and server handling  
- **MongoDB & Mongoose** – Database and schema modeling  
- **EJS** – Templating engine for dynamic HTML  
- **Bootstrap** – Sleek and mobile-ready UI  
- **Passport.js** – User authentication  
- **Cloudinary** – Image upload & management  
- **Render** – Live deployment and hosting

---

## ✨ Key Features

- 📸 Add and manage property listings  
- 👥 Register/login as guest or host  
- 💬 Post and view reviews for each property  
- 📱 Fully responsive on desktop, tablet, and mobile  
- 🧼 Clean, minimal, user-friendly interface

---

## 🌐 Live Website & Hosting

- 🔗 [Visit WanderLust](https://wanderlust-qgxn.onrender.com/listings)  
- 🚀 **Hosted on:** Render – scalable deployment for Node.js apps
