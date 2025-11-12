<h1 align="center">🏡 HomelyHub – Airbnb Booking Platform (MERN Stack)</h1>

<p align="center">
  <b>A Full-Stack Airbnb-inspired web application built using the MERN Stack.</b>  
  <br>
  Book your perfect stay, list your property, and manage bookings — all in one modern platform.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/Mongoose-e10098?style=for-the-badge&logo=mongoose&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white"/>
</p>

---

## ✨ Overview

**HomelyHub** is an Airbnb-like property booking platform built using the **MERN stack (MongoDB, Express, React, Node.js)**.  
It enables users to **book short-term stays**, **list rental properties**, **manage reservations**, and **connect with hosts** — all through an intuitive and responsive interface.

---

## 🧩 Tech Stack

| Component | Technology | Description |
|------------|-------------|-------------|
| **Frontend** | React.js + Redux | Modern, responsive user interface with state management |
| **Backend** | Node.js + Express.js | RESTful API server and authentication handling |
| **Database** | MongoDB + Mongoose | Flexible NoSQL database for properties, bookings, and users |
| **Auth** | JWT (JSON Web Token) | Secure authentication for users and hosts |
| **Styling** | CSS / Tailwind | Clean and responsive UI styling |

---

## 🌟 Features

🏠 **Property Listings** – Browse available homes, villas, and apartments.  
🧑‍💻 **Host Dashboard** – List properties with details, photos, and pricing.  
📅 **Booking System** – Real-time property booking and reservation tracking.  
🔐 **User Authentication** – Secure signup, login, and session handling via JWT.  
💬 **Messaging** – Connect guests and hosts within the platform.  
❤️ **Wishlist** – Save favorite properties for quick access later.  
📱 **Responsive Design** – Optimized for desktop, tablet, and mobile screens.  
🧾 **Admin Panel** – Manage users, bookings, and property listings.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/HomelyHub-An-Airbnb-booking-Website.git
cd HomelyHub-An-Airbnb-booking-Website
```

### 2️⃣ Set Up Environment Variables
Create a `.env` file inside the `backend/` folder:
```bash
MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret
CLOUDINARY_URL=your-cloudinary-api-key
PORT=5000
```

### 3️⃣ Install Dependencies
```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### 4️⃣ Run the Application
```bash
# Backend server
cd backend
npm start

# Frontend client
cd ../frontend
npm run dev
```

### 5️⃣ Access the App
```
http://localhost:5173/
```

---

## 🗂 Folder Structure

```
HomelyHub/
│
├── backend/             # Node.js + Express.js API
│   ├── config/          # MongoDB connection, environment setup
│   ├── models/          # Mongoose models (User, Property, Booking)
│   ├── routes/          # Express routes (auth, properties, bookings)
│   ├── controllers/     # Route logic and data processing
│   ├── utils/           # JWT, middleware, error handling
│   └── server.js
│
├── frontend/            # React.js frontend
│   ├── src/
│   │   ├── components/  # Navbar, Footer, Cards, etc.
│   │   ├── pages/       # Home, Property, Booking, Profile
│   │   ├── redux/       # Redux state management
│   │   └── App.js
│   ├── public/
│   └── package.json
│
└── README.md
```

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| `POST` | `/api/auth/register` | Register new user or host |
| `POST` | `/api/auth/login` | Login existing user |
| `GET` | `/api/properties` | Get all property listings |
| `POST` | `/api/properties` | Add a new property (host only) |
| `GET` | `/api/properties/:id` | Get property by ID |
| `POST` | `/api/bookings` | Book a stay |
| `GET` | `/api/bookings/user/:id` | Get bookings for a user |

📘 *Full route details available in* [`backend/routes`](./backend/routes)

---

## 🧑‍💻 Contributing

Contributions are welcome!  
To contribute:
1. Fork this repo  
2. Create a feature branch  
3. Commit your changes  
4. Submit a Pull Request 🚀  

---

## 📄 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- **Mentor:** Mrs. *Richa Jha*  
- **Developed by:** [Asish Sarangi](https://www.linkedin.com/in/asish-sarangi-8a33322a6)  
- **Internship:** Web Stack Academy (WSA)

---

## 🌐 Connect with Me

<p align="center">
  <a href="https://github.com/asish915"><img src="https://img.shields.io/badge/GitHub-asish915-black?style=for-the-badge&logo=github"/></a>
  <a href="https://www.linkedin.com/in/asish-sarangi-8a33322a6"><img src="https://img.shields.io/badge/LinkedIn-Asish%20Sarangi-blue?style=for-the-badge&logo=linkedin"/></a>
  <a href="mailto:asishsarangi2005@gmail.com"><img src="https://img.shields.io/badge/Email-asishsarangi2005@gmail.com-red?style=for-the-badge&logo=gmail"/></a>
</p>

---

> 🌍 *HomelyHub – Find your next stay, anywhere, anytime.*
