# 🐾 Petique Clinic Management System

> 📌 **Note:** This repository is a personal fork of the original graduation project. Below are the specific core frontend features, state management architecture, and user flows that **I personally developed and engineered**.

---

## 🚀 My Core Contributions & Technical Achievements

* **Service Display & Dynamic Routing:** Developed the scalable structure for fetching and rendering clinic services, including the complex single service details page with dynamic route management.
* **Reservation System & User Flow:** Implemented the complete front-end reservation and booking flow, ensuring a seamless user experience and strict synchronization between user inputs and backend state.
* **Dashboard Email Management:** Developed the dedicated management interface and logic within the admin dashboard for handling, tracking, or triggering automated system emails.
* **Dashboard Reservation Form Validation:** Engineered robust client-side form validations for almost all reservation-related forms inside the dashboard, utilizing advanced control logic to ensure data integrity and prevent faulty submissions.
* **Content Delivery (Blog Section):** Built the dynamic Blog and article grid section, utilizing state management and clean UI layout principles to present pet care resources beautifully.

---

Petique Clinic is a full-stack veterinary clinic management platform designed to serve pet owners, doctors, administrators, and clinic owners.
The system manages reservations, vaccinations, services, and products through role-based access and multiple dashboards.

---

## 🚀 Project Overview

Petique Clinic enables:

- Easy appointment booking for pet owners
- Reservation and medical record management for doctors
- Product and service management for admins
- Full business control and analytics for owners
- Ai integration through ChatBot text prediction and image analyzing for pets disease 

The platform consists of **4 websites** and **5 user roles**.

---

## 👥 User Roles

### 🐶 Pet Owner

- Sign up & login 
- Google OAuth signup & login
- Email verification & OTP
- Forget & reset password
- Add and manage pets
- Book reservations (doctor, date, time, service)
- View reservation history
- Track vaccination records
- View & track orders
- Reservation & vaccination reminders
- Full notification system

### 👨‍⚕️ Doctor

- View assigned reservations
- Manage daily schedule
- Add vaccinations & medical notes
- Update reservation status
- Notifications for reservations & services

### 🛠️ Admin Shopping

- Manage users & product-related support emails
- Manage products & Categories & coupons & orders
- View analytics & reports 
- Order notifications

### 👑 Owner

- Full system access
- Manage admins & doctors
- Access all dashboards
- Monitor clinic performance

---

## 🔐 Test Credentials

Use the following credentials to explore the different system functionalities:

| Role | Email | Password |
| :--- | :--- | :--- |
| **Owner** | `yumnamohamed30@gmail.com` | `Yomn123` |
| **Doctor** | `doctor@gmail.com` | `Yomna123` |
| **Pet Owner** | `yomnaelshorbage@gmail.com` | `Yomn123` |
| **Staff** | `yomnamo@gmail.com` | `Yomna123` |
| **Seller** | `seller@gmail.com` | `Yomna123` |

---

## 🌐 Websites & Access
1. **Pet Owner Website**: Main portal for pet services, shopping, and AI assistance.
2. **Seller Dashboard**: E-commerce and product management.
3. **Doctor Dashboard**: Clinical appointment and patient management.
4. **Staff Dashboard**: Clinic operations, reservations, and client relations.
5. **Owner Dashboard**: Full administrative oversight and clinic analytics.

---

## 📅 Reservation Workflow
`PENDING` → `CONFIRMED` → `COMPLETED`  
`CANCELED`

---

## 💉 Vaccination Management
- Linked to pet, doctor, and reservation.
- Editable by doctors, staff, owner and managed by status.
- Automatic next dose calculation and email reminders.
- Full audit logs viewable by clinic owner.

---

## 🌟 Detailed Features

### 👤 3.2 - User Profile
A multi-tabbed interface for comprehensive pet and account management:
- **Profile Data**: Edit personal information and upload profile images.
- **Add Animal**: Register new pets into the clinic system.
- **My Animals**: Directory of all pets added by the user.
- **Order History**: View all past orders for animal products.
- **Order Tracking**: Real-time status updates on product deliveries.
- **Reservation Tracking**: Monitor upcoming and past clinical visits.
- **Shopping Analysis**: Insights into completing orders products with analysis summary.
- **AI Symptom Checker**: Predict actions based on pet symptoms and save history for review.

### 📞 3.9 - Contact Us
- **Contact Form**: Direct messaging to clinic support.
- **About Section**: Comprehensive clinic info with a **QR Code** for quick site access.
- **Direct Connect**: Icons to launch real-time chats with **Sellers**, **Staff**, and **Doctors**.

### 🤖 3.12 - AI Assistant
- **Disease Prediction**: Advanced AI chat predicting diseases using both **text input** and **image analysis**.

---

## 🛠️ Dashboard Architecture

All dashboard pages feature a consistent design language:
- **Actions**: ADD, EDIT, SOFT DELETE, HARD DELETE.
- **UI Components**: Shared tables with advanced Filtering and Pagination.

### 🛒 4 - Seller Dashboard
- **4.1 Overview**: Analytics for users, products, categories, and revenues.
- **4.2 Users**: Manage customer accounts.
- **4.3 Products & 4.4 Categories**: Full inventory and catalog control.
- **4.5 Orders**: Track and fulfill customer purchases.
- **4.6 Reports**: Business intelligence and full needed reports & managing printing it 
- **4.7 Emails**: Support system to replay for all users Queries and questions.
- **4.8 Chat**: Real-time interaction with pet owners.
- **4.9 Archive**: View all archived products and categories and all soft deleted data and ability to restore them.

### 🩺 5 - Doctor Dashboard
- **5.1 Overview**: Clinical summary and daily performance.
- **5.2 Reservations**: Manage and update patient appointments.
- **5.3 Pet Categories & 5.4 Pets**: Access detailed patient records.
- **5.5 Vaccinations**: Manage immunization schedules.
- **5.6 Chat**: Direct clinical communication with pet owners.
- **6.7 Doctor Profile**: Manage their own data and update it.

### 🏥 6 - Staff Dashboard (Clinic Operations)
- **6.1 New Reservations**: Onboard new clients and pets.
- **6.2 Appointment Center**: View and update all appointments; manage rescheduling.
- **6.3 Clients**: View full client history (reservations, pets, vaccinations).
- **6.4 Pets History**: Detailed vaccination tracking and next dose monitoring.
- **6.5 Vaccination Management**: Complete or reschedule immunization tasks.
- **6.6 Chat**: Real-time coordination with pet owners.

### 👑 7 - Owner Dashboard
- **Full Access**: Includes all functionalities of Staff and Seller dashboards.
- **7.1 Doctors & 7.2 Staff Management**: Complete personnel oversight.
- **7.3 Executive Chat**: Direct line to pet owners.
- **7.4 Analytics**: High-level clinic overview and complex business analysis.

---

## 🌍 Localization
The platform supports **4 languages**, providing a local experience for a global user base.
- (Arabic - English - German - French)
---

## 🛠️ Tech Stack

### Frontend

- React / React Native
- TypeScript
- Redux Toolkit
- React Query
- Zod
- i18next
- Tailwind CSS

### Backend

- Node.js
- Express.js
- Mongo Atlas + Mongoose
- JWT Authentication
- Role-based authorization
- Cloudinary (images)
- Stripe (payments)
- Notification management system

---

## 🔄 Application Workflow & Architecture

### API-Driven Design

- RESTful APIs
- Role-based access control
- Pagination & filtering
- Soft delete strategy
- Centralized error handling

### State Management

- Redux Toolkit for global state:
  - Auth
  - Cart & orders
  - Notifications
  - UI state

### Server State

- React Query for:
  - Data fetching
  - Caching
  - Background refetching
  - Optimistic updates

---

## 🪝 Custom Hooks for APIs

Reusable hooks wrap API logic

Benefits:

- Clean components
- Reusable logic
- Type-safe APIs

---

## 📄 Pagination & Filtering

Implemented for:

- Reservations
- Orders
- Products
- Users
- and more needed ...

Handled using:

- Backend query params
- Reusable pagination component
- Cached query states

---

## 🧩 Shared Components

Reusable UI components across all dashboards:

- StatCard
- Tables
- Modals
- Forms (Zod validation)
- Badges & buttons & inputs
- Loaders & empty states

---

## 🔔 Notifications System

- Reservation reminders
- Vaccination reminders
- Order updates
- Doctor schedule alerts

Channels:

- In-app notifications
- Email notifications

---

## 📁 Project Structure
```text
petique-clinic/
├── backend/                  # Node.js API
├── pet-owner-frontend/       # Client Web App
├── doctor-dashboard/         # Clinical Portal
├── admin-dashboard/          # Seller/Staff/Owner Dashboards
└── README.md
```

---
## 🐾 Petique Clinic

Smart Care for Every Pet
