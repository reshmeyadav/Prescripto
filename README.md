<h1 align="center">
  <img alt="Prescripto" src="https://res.cloudinary.com/deqewgc25/image/upload/v1753348664/favicon_tszlye.svg" width="55"/>
  <br>
  Prescripto: Doctor Appointment Management System
</h1>

---

<div align="center">

<!-- **GitHub Badges** -->
[![GitHub last commit](https://img.shields.io/github/last-commit/pranshu-tomer/Prescripto)](https://github.com/pranshu-tomer/Prescripto/commits/main)
[![GitHub contributors](https://img.shields.io/github/contributors/pranshu-tomer/Prescripto)](https://github.com/pranshu-tomer/Prescripto/graphs/contributors)
[![GitHub stars](https://img.shields.io/github/stars/pranshu-tomer/Prescripto)](https://github.com/pranshu-tomer/Prescripto/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/pranshu-tomer/Prescripto)](https://github.com/pranshu-tomer/Prescripto/network/members)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

<!-- **Technology Icons** using Shields.io and Devicons -->
<div>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" alt="Redux"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" alt="JWT"/>
</div>
</div>

---

## Overview

Prescripto is a **web-based appointment management system** designed for healthcare providers, allowing admins to **register doctors** and **patients to book appointments seamlessly**. The platform modernizes healthcare scheduling with real-time booking, multi-role authentication, integrated payments, and digital prescription capabilities.

Key highlights:
- **Admin**: Register/manage doctors, oversee system analytics.
- **Doctor**: Manage appointments, issue prescriptions, update availability.
- **Patient**: Search doctors, book appointments, view prescriptions.
- **Secure**: JWT authentication, encrypted data, PCI-compliant payments.
- **Responsive**: Works on desktop, tablet, and mobile.

---

## Live Preview

Try out **Prescripto** using the links and demo credentials below for each user role.

### 🔗 Application Links

- **Doctor & Admin Portal:** [https://dockit-admin.netlify.app/](https://dockit-admin.netlify.app/)
- **User Portal:** [https://dockit.netlify.app/](https://dockit.netlify.app/)

### 🧑‍💼 Admin Login

- **Email:** admin@gmail.com
- **Password:** admin1234

### 👨‍⚕️ Demo Doctor Login

- **Email:** rishu@gmail.com
- **Password:** 12345678

### 🙍‍♂️ Demo User Login

- **Email:** demo@gmail.com
- **Password:** 12345678

---

## Features

✔ **Multi-role Authentication**  
✔ **Doctor Directory & Management**  
✔ **Real-time Appointment Booking**  
✔ **Reschedule/Cancel Appointments**  
✔ **Digital Prescription Issuance**  
✔ **Integrated Payment Gateway**  
✔ **Real-time Notifications**  
✔ **User & Admin Dashboards**  
✔ **Responsive, Modern UI**

---

## Screenshots

<!-- Add your screenshots here (replace with actual paths if available) -->
| Homepage | Patient Dashboard | Doctor Dashboard | Admin Panel |
|----------|-------------------|------------------|-------------|
| ![Homepage](https://res.cloudinary.com/deqewgc25/image/upload/v1753349213/Screenshot_2025-07-24_145601_wtjme6.png) | ![Patient](https://res.cloudinary.com/deqewgc25/image/upload/v1753349320/Screenshot_2025-07-24_145817_wnncmw.png) | ![Doctor](https://res.cloudinary.com/deqewgc25/image/upload/v1753349637/Screenshot_2025-07-24_150337_xowyfu.png) | ![Admin](https://res.cloudinary.com/deqewgc25/image/upload/v1753349455/Screenshot_2025-07-24_150031_hywb3e.png) |

---

## Tech Stack

Here’s a quick look at the technologies used in this project.

| Layer      | Technology                       | Icon |
|------------|----------------------------------|------|
| Frontend   | React, Redux, Tailwind CSS       | <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" width="100"/> |
| Backend    | Node.js, Express.js              | <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" width="80"/> |
| Database   | MongoDB                          | <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" width="90"/> |
| Auth       | JWT                              | <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" width="70"/> |
| UI/UX      | Material UI, Chart.js            | <img src="https://img.shields.io/badge/Material%20UI-007FFF?style=for-the-badge&logo=mui&logoColor=white" width="100"/> |
| Payments   | Razorpay/Stripe                  | <img src="https://img.shields.io/badge/Razorpay-02042B?style=for-the-badge&logo=razorpay&logoColor=3395FF" width="100"/> |


---

## Installation & Usage

### Prerequisites

- Node.js (v16+ recommended)
- npm / yarn
- MongoDB Atlas or local instance
- Stripe/Razorpay API keys (for payments)

### Installation

1. **Clone the repository**
```

git clone https://github.com/pranshu-tomer/Prescripto.git
cd Prescripto

```

2. **Set up backend**
```

cd backend
npm install

```
Create `.env` file in `/backend` and add:
```

MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PAYMENT_PROVIDER_KEY=your_payment_api_key

```
Start backend server:
```

npm run dev

```

3. **Set up frontend**
```

cd ../frontend
npm install

```
Start frontend development server:
```

npm run dev

```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Usage

- **Admin**: Register doctors, manage users, view analytics.
- **Doctor**: Accept/reject appointments, issue prescriptions.
- **Patient**: Search doctors, book appointments, view prescription history.

---

<p align="center"> 
<b>Made with ❤ by Pranshu Tomer and contributors.</b>
</p>
