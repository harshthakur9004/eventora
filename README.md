# Eventora - MERN Event Booking Platform

Eventora is a full-stack event booking application where users can browse events and book tickets, while admins manage bookings.

## Features

- User registration / login (JWT + bcrypt)
- Email OTP verification (to activate accounts and confirm bookings)
- Role-based access: User and Admin
- Admin: Create / edit / delete events, confirm / reject bookings
- Booking requests are added to a "Pending" queue, and the admin approves them
- Seat availability check (to prevent overbooking)
- Admin dashboard: Pending requests and revenue
- Booking confirmation emails using Nodemailer

## My Contributions

- ___ (e.g., Added event search / filter functionality)
- ___ (e.g., Built the user profile page)

## Tech Stack

- Frontend: React, Tailwind CSS, Vite
- Backend: Node.js, Express
- Database: MongoDB (Mongoose)
- Email: Nodemailer

## Run Locally

### 1. Environment Variables

Copy `server/.env.example` to `server/.env` and fill in the following:

```env
MONGO_URI=
JWT_SECRET=
EMAIL_USER=
EMAIL_PASS=
PORT=5000
```

`EMAIL_PASS` requires a Gmail App Password.

### 2. Install and Run

In the terminal:

```bash
cd server
npm install --legacy-peer-deps
npm run dev
```

In a new terminal:

```bash
cd client
npm install
npm run dev
```

Frontend runs at `http://localhost:5173` and the backend runs at `http://localhost:5000`.


