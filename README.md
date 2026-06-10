# 🌍 Silkway Travel - Uzbekistan Tourism Platform

## 📌 Project Overview

**Full-Stack Tourism Platform** for tourists visiting Uzbekistan with complete features:

✅ **3 Languages:** Uzbek, Russian, English
✅ **SMS Registration:** Phone-based with 7-digit OTP
✅ **AI Guide System:** Smart recommendations based on user profile
✅ **Hotel Management:** Browse and book hotels
✅ **Restaurant System:** Find and review restaurants
✅ **Tour Packages:** Curated tour experiences
✅ **Admin Panel:** Complete management system
✅ **Payment System:** Secure card payments
✅ **Charity:** 2-3% donation to Leukemia patients
✅ **Telegram Bot:** Real-time notifications
✅ **Real-time Data:** Weather, currency rates, nearby amenities

## 🚀 Quick Start

### Installation
```bash
# Clone the repository
git clone https://github.com/boburxoja10122005-ui/SilkWayy.uzTravel.git
cd SilkWayy.uzTravel

# Install dependencies
npm install

# Create .env file
cp .env.example .env

# Update .env with your credentials

# Start development server
npm run dev
```

## 📁 Project Structure

```
├── models/              # MongoDB schemas
│   ├── User.js
│   ├── Hotel.js
│   ├── Tour.js
│   └── Payment.js
├── routes/              # API endpoints
│   ├── auth.js
│   ├── hotels.js
│   ├── tours.js
│   ├── payments.js
│   └── admin.js
├── middleware/          # Authentication
│   └── auth.js
├── utils/               # Utilities
│   ├── sms.js
│   └── email.js
├── server.js            # Main application
├── package.json         # Dependencies
└── README.md           # This file
```

## 🌐 API Endpoints

### Authentication
- `POST /api/auth/register` - Register with phone number
- `POST /api/auth/verify-otp` - Verify OTP code
- `POST /api/auth/complete-profile` - Complete user profile

### Hotels
- `GET /api/hotels` - Get all hotels with filters
- `POST /api/hotels/add` - Add new hotel

### Tours
- `GET /api/tours` - Get all tour packages
- `POST /api/tours/create` - Create tour package

### Payments
- `POST /api/payments/create` - Process payment
- `GET /api/payments/history` - Get payment history

### Admin
- `GET /api/admin/stats` - Dashboard statistics
- `POST /api/admin/add-restaurant` - Add restaurant

## 🔑 Key Features

✅ Phone-based registration with SMS OTP
✅ Profile completion with birth date
✅ Hotel and restaurant management
✅ Tour package recommendations
✅ Secure payment processing
✅ Payment history tracking
✅ Charity donation system (2-3% to Leukemia)
✅ Promo code support (UZBEKISTON2026)
✅ Admin dashboard
✅ Real-time data integration

## 📧 Email Notifications

All transactions send to: `boburxoja10122005@gmail.com`

## 💳 Payment Card

**Card:** 9860020107613240
**Owner:** Siddiqov Boburxoja

## 🤖 Telegram Bot

**Token:** `7769158984:AAEpj4Q4ekGR0wp0DIBUzQL4G20KT9KXBu0`

## 🌐 Deployment

**Domain:** silkwayytravel.linkpc.net
**IP:** 37.110.214.2

---

**Status:** 🚀 Active Development