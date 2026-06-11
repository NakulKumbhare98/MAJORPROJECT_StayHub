# StayHub – Luxury Stays & Unique Getaways

StayHub is a full-stack property rental platform inspired by modern accommodation booking services. Built using Node.js, Express.js, MongoDB, and Cloudinary, it enables users to explore, create, and manage property listings with secure authentication and seamless image upload functionality.

---

## 🌐 Live Demo

👉 https://majorproject-stayhub.onrender.com

---

## 💻 GitHub Repository

👉 https://github.com/NakulKumbhare98/MAJORPROJECT_StayHub

---

## 🚀 Features

- Search listings by title, location, or country
- Filter listings by category
- Create, edit, and delete listings
- User authentication (Register/Login/Logout)
- Add reviews and ratings
- Interactive map with geo-location
- Image upload using Cloudinary
- Protected routes for logged-in users
- Fully responsive design

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- EJS (templating)

### Backend
- Node.js
- Express.js

### Database
- MongoDB Atlas
- Mongoose ODM

### Authentication
- Passport.js
- Express-session

### Cloud Services
- Cloudinary (image storage)
- OpenStreetMap API (Nominatim for geocoding)

---

## 📁 Project Structure

```text
Project-StayHub/
├── controllers/          # Request handlers
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
├── models/             # Database schemas
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── routes/             # Route definitions
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── views/              # EJS templates
│   ├── includes/
│   ├── layouts/
│   ├── listings/
│   └── user/
├── public/             # Static files
│   ├── css/
│   └── js/
├── utils/              # Utility functions
├── init/               # Database initialization
├── middleware.js       # Middleware functions
├── app.js              # Main application file
├── cloudConfig.js      # Cloudinary configuration
└── package.json       # Dependencies
```


---

## 🔐 Authentication

- User registration and login system
- Session-based authentication with Passport.js
- Protected routes for creating, editing, and deleting listings
- Ownership validation (users can only modify their own listings)

---

## 🗺️ Map Feature

- Uses OpenStreetMap API (Nominatim) for geocoding
- Converts location addresses to coordinates
- Stores GeoJSON in MongoDB
- Displays interactive map with Leaflet.js

---

## 📸 Image Upload

- Cloudinary integration for image storage
- Secure file upload handling
- Image URL and filename saved in database

---

## ⭐ Show Your Support

If you like this project:

1. ⭐ Star the repository
2. 🍴 Fork it
3. 🔥 Improve it

---


*Built with ❤️ using Node.js, Express, MongoDB, EJS, and Cloudinary*

