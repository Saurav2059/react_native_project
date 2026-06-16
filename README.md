# 🏡 Kribb - Full Stack Real Estate Mobile App

> A modern full-stack real estate marketplace built with React Native, Expo, TypeScript, Supabase, Clerk Authentication, and NativeWind.

![Platform](https://img.shields.io/badge/Platform-iOS%20%26%20Android-blue)
![React Native](https://img.shields.io/badge/React%20Native-Latest-61DAFB)
![Expo](https://img.shields.io/badge/Expo-SDK-black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📱 About The Project

Kribb is a modern real estate marketplace mobile application that allows users to browse, search, save, and manage property listings.

The application provides a seamless experience for discovering apartments, villas, houses, and studios while offering secure authentication and scalable backend infrastructure.

Built with a production-ready full-stack architecture using:

* React Native
* Expo Router
* TypeScript
* Supabase
* Clerk Authentication
* NativeWind (Tailwind CSS)
* Zustand State Management

---

## ✨ Features

### 🔐 Authentication

* Secure Clerk Authentication
* User Registration
* User Login
* Protected Routes
* User Profile Management

### 🏘 Property Listings

* Browse Available Properties
* Featured Properties Section
* Property Details Screen
* Property Image Galleries
* Property Categories

### ❤️ Saved Properties

* Save Favorite Properties
* Remove Saved Properties
* Personalized Saved Listings

### 🔍 Search & Discovery

* Search Properties
* Browse by Category
* Filter Listings
* Featured Recommendations

### 👨‍💼 Admin Features

* Create Property Listings
* Update Existing Listings
* Delete Properties
* Upload Property Images
* Role-Based Access Control

### ☁ Backend Features

* PostgreSQL Database
* Row Level Security (RLS)
* Secure Storage Buckets
* Authentication Policies
* Scalable Cloud Infrastructure

---

## 🛠 Tech Stack

### Frontend

* React Native
* Expo
* Expo Router
* TypeScript
* NativeWind
* Zustand

### Backend

* Supabase
* PostgreSQL
* Supabase Storage

### Authentication

* Clerk

### Styling

* Tailwind CSS
* NativeWind

---

## 📂 Project Structure

```bash
app/
components/
hooks/
lib/
store/
types/
assets/

app.json
package.json
tailwind.config.js
metro.config.js
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

* Node.js
* npm
* Expo CLI
* Android Studio (Android Emulator)
* Xcode (Mac only for iOS Simulator)

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/react_native_project.git
```

Navigate into the project:

```bash
cd react_native_project
```

Install dependencies:

```bash
npm install
```

---

## ▶ Running the Application

Start the development server:

```bash
npx expo start -c
```

You can then run the application using:

* Android Emulator
* iOS Simulator
* Expo Go
* Development Build

---

## 🔑 Environment Variables

Create a `.env` file in the root directory.

```env
EXPO_PUBLIC_SUPABASE_URL=
EXPO_PUBLIC_SUPABASE_ANON_KEY=

EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=
```

---

## 🗄 Database Schema

### Users Table

Stores authenticated user information.

Fields include:

* clerk_id
* email
* first_name
* last_name
* avatar_url
* is_admin

### Properties Table

Stores all real estate listings.

Fields include:

* title
* description
* price
* type
* bedrooms
* bathrooms
* area_sqft
* city
* address
* images

### Saved Properties Table

Allows users to save favorite listings.

---

## 🔒 Security

Supabase Row Level Security (RLS) is enabled for:

* Users
* Properties
* Saved Properties
* Storage Buckets

Admin users can:

* Create Properties
* Edit Properties
* Delete Properties
* Upload Images

Regular users can:

* View Properties
* Save Properties
* Manage Favorites

---

## 📸 Screenshots

Add your screenshots here.

### Home Screen

```text
assets/screenshots/home.png
```

### Property Details

```text
assets/screenshots/property-details.png
```

### Saved Properties

```text
assets/screenshots/saved-properties.png
```

---

## 🌟 Featured Property Types

* Apartment
* House
* Villa
* Studio

---

## 📈 Future Improvements

* Property Booking System
* In-App Chat
* Property Reviews
* Advanced Search Filters
* Push Notifications
* Map-Based Search
* AI Property Recommendations

---

## 👨‍💻 Author

**Saurav**

GitHub: https://github.com/Saurav2059

---

## ⭐ Support

If you found this project useful, please consider giving it a star ⭐ on GitHub.

It helps others discover the project and supports future development.

---

## 📄 License

This project is licensed under the MIT License.
