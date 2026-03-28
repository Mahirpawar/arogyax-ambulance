# 🚑 ArogyaX Ambulance Module

An Uber/Ola-inspired **real-time ambulance booking system** built as part of the ArogyaX healthcare platform.

This module enables users to quickly find, compare, and book nearby ambulances with estimated arrival time, pricing, and emergency support.

---

## 🌟 Features

* 📍 **Live Location-Based Search**

  * Detects user location
  * Shows nearby ambulances

* 🚑 **Multiple Ambulance Types**

  * General Purpose Ambulance
  * Basic Life Support (BLS)
  * Mobile ICU

* ⏱️ **ETA (Estimated Time of Arrival)**

  * Displays how quickly ambulance will arrive
  * Optimized for emergency response

* 💰 **Price Comparison**

  * Compare ambulance costs before booking

* ⚡ **Quick Booking System**

  * One-click ambulance booking

* ☎️ **Emergency Integration**

  * Option to call **108 (Government Ambulance - Free)**

---

## 🧠 Problem Statement

In India, emergency response systems often suffer from delays and lack of accessibility.
There is no unified platform that provides:

* Fast ambulance booking
* Price transparency
* Real-time tracking

---

## 💡 Solution

ArogyaX Ambulance Module bridges this gap by combining:

* Real-time ambulance discovery
* Smart ETA calculation
* Cost comparison
* Emergency fallback (108 service)

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Realtime (Optional)

* Socket.io

### Maps (Optional)

* Google Maps API / Mapbox

---

## 📁 Project Structure

```
ambulance-module/
│
├── client/                 # React Frontend
│   ├── components/
│   │     └── AmbulanceUI.jsx
│   └── App.js
│
├── server/                 # Backend (Node + Express)
│   ├── routes/
│   │     └── ambulanceRoutes.js
│   └── server.js
│
├── README.md
```

---

## 🔌 API Endpoints

### 🔹 Get Nearby Ambulances

```
GET /ambulances/nearby
```

Response:

```
[
  {
    "type": "General",
    "eta": 5,
    "price": 500
  },
  {
    "type": "BLS",
    "eta": 3,
    "price": 1200
  }
]
```

---

### 🔹 Book Ambulance

```
POST /ambulance/book
```

---

## 🚀 How to Run Locally

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/ambulance-module.git
cd ambulance-module
```

---

### 2️⃣ Run Backend

```
cd server
npm install
npm start
```

---

### 3️⃣ Run Frontend

```
cd client
npm install
npm start
```

---

## ⚠️ Note

* This module currently uses **mock data** for hackathon/demo purposes
* Can be easily extended with:

  * Real-time GPS tracking
  * Database integration (MongoDB)
  * Live ambulance APIs

---

## 🔮 Future Enhancements

* 📡 Live ambulance tracking (Socket.io)
* 🗺️ Map integration with routes
* 💳 Online payment system
* 🏥 Hospital integration
* 📊 AI-based emergency prioritization

---

## 🎯 Use Case

This module is part of **ArogyaX**, a complete AI-powered healthcare ecosystem that includes:

* AI health assistant
* Doctor consultation
* Medicine comparison
* Emergency ambulance booking

---

## 👨‍💻 Author

**Mahir Singh Pawar**
B.Tech CSE (Data Science)
Backend & App Developer

---

## ⭐ Contribute

Feel free to fork this repository and improve the system.

---

## 📌 Final Note

This project demonstrates how technology can reduce emergency response time and make healthcare more accessible and efficient.

🚑 “Because every second matters in an emergency.”
