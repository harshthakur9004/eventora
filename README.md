# Eventora - MERN Event Booking Platform

> **Original project:** https://github.com/ShivaMani02/Eventora-MERN
> Maine is open source project ko clone karke uska code study kiya aur apni learning ke liye isme changes kiye hain.

Eventora ek full-stack event booking application hai jisme users events dekh kar tickets book kar sakte hain, aur admin bookings ko manage karta hai.

## Features

- User register / login (JWT + bcrypt)
- Email OTP verification (account activate karne ke liye aur booking confirm karne ke liye)
- Role-based access: User aur Admin
- Admin: event create / edit / delete, booking confirm / reject
- Booking request "Pending" queue me jati hai, admin approve karta hai
- Seat availability check (overbooking se bachav)
- Admin dashboard: pending requests aur revenue
- Nodemailer se booking confirmation email

## Mere Changes (My Contributions)

- ___ (jaise: event search / filter add kiya)
- ___ (jaise: user profile page banaya)

## Tech Stack

- Frontend: React, Tailwind CSS, Vite
- Backend: Node.js, Express
- Database: MongoDB (Mongoose)
- Email: Nodemailer

## Local me Run Kaise Karein

### 1. Environment variables

`server/.env.example` ko copy karke `server/.env` banao aur apni values bharo:

    MONGO_URI=
    JWT_SECRET=
    EMAIL_USER=
    EMAIL_PASS=
    PORT=5000

`EMAIL_PASS` ke liye Gmail ka App Password chahiye.

### 2. Install aur run

    cd server
    npm install --legacy-peer-deps
    npm run dev

Naye terminal me:

    cd client
    npm install
    npm run dev

Frontend `http://localhost:5173` par aur backend `http://localhost:5000` par chalega.


