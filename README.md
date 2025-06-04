# Concierge Digital App – Squad 18 (Accenture)

A complete web platform for corporate event management with a focus on modern digital experience, intelligent networking and efficient management of agendas and speakers.

---

## 📑 Index

1. [📋 System Overview](#-system-overview)
2. [🚀 Features](#-features)
3. [🛠️ Technologies Used](#-technologies-used)
4. [✅ Prerequisites](#-prerequisites)
5. [📁 Project Structure](#-project-structure)
6. [🚀 Installation and Execution Steps](#-installation-and-execution-steps)
7. [🧪 Test the Application](#-test-the-application)
8. [🔌 Future Integrations (Planned)](#-future-integrations-planned)
9. ​​[⚠️ License](#️-license)

---

## 📋 System Overview

**Concierge Digital App** is a web system developed for the complete management of corporate events, focused on providing a modern and integrated experience for participants, speakers and organizers.

---

## 🚀 Features

- 🔐 **Secure Authentication** with corporate email and verification code
- 📊 **Smart Dashboard** with dynamic cards and AI search
- 🎤 **Speaker Management** with profiles, modals and favorites
- 🗓️ **Dynamic Programming** with registrations, filters and vacancy control
- 🧾 **Personal Agenda** with visual conflicts and synchronization
- 📷 **QR Scanner & Networking** for automatic check-in and contact exchange
- 🧑‍💼 **Digital Profile with QR Code** for professional networking
- ❓ **Categoried Help Center (FAQ)** with smart search
- 📱 **Responsive Design & Glassmorphism** prepared for mobile-first

---

## 🛠️ Technologies Used

### **Frontend**
- `React 18.3.1` – Core UI framework
- `React Router DOM 6.23.1` – SPA routing system
- `Context API` – Global state management
- `Lucide React 0.263.1` – Modern icon library

### **Stylization**
- `CSS Modules` – Componentized and modular styling
- `Glassmorphism` – Design with transparency and depth
- `Mobile-first Design` – Prioritizing the mobile experience

### **Build & Development**
- `Vite 5.2.11` – Lightweight and performant build tool
- `ESLint 8.57.0` – Linter for standardization and code quality
- `@vitejs/plugin-react 4.3.0` – Official React plugin for Vite

### **Special Features**
- `QR Scanner 1.4.2` – QR code reading for networking and check-in
- `LocalStorage` – Local storage of session data
- `Progressive Enhancement` – Progressive improvement of features
- `PWA Ready` – Progressive Web App support

---

## 📦 Deployment Instructions

Below we describe the complete step-by-step process for deploying the Concierge Digital App project, allowing anyone to run the application from scratch, in a new environment.

---

## ✅ Prerequisites

- [Node.js](https://nodejs.org/) v16 or higher
- Git (optional)
- Modern browser (Chrome, Firefox, Edge)
- Code editor (VS Code recommended)

---

## 📁 Project Structure

```
concierge-digital-app/
├── public/
│ ├── index.html
│ ├── accenture-logo.png
│ └── vite.svg
├── src/
│ ├── components/
│ │ ├── Loading.jsx
│ │ ├── Loading.css
│ │ ├── QRScanner.jsx
│ │ ├── QRScanner.css
│ │ ├── SpeakerModal.jsx
│ │ └── SpeakerModal.css
│ ├── context/
│ │ └── AuthContext.jsx
│ ├── pages/
│ │ ├── Agenda.jsx
│ │ ├── Agenda.css
│ │ ├── FAQ.jsx
│ │ ├── FAQ.css
│ │ ├── Login.jsx
│ │ ├── Login.css
│ │ ├── Speakers.jsx
│ │ ├── Speakers.css
│ │ ├── Profile.jsx
│ │ ├── Profile.css
│ │ ├── QRCode.jsx
│ │ ├── QRCode.css
│ │ ├── Schedules.jsx
│ │ ├── Schedules.css
│ │ └── Welcome.jsx
│ ├── App.jsx
│ ├── App.css
│ ├── index.css
│ └── main.jsx
├── .gitignore
├── eslint.config.js
├── package.json
├── package-lock.json
├── README.md
└── vite.config.js
```

> If you don't have these files yet, clone the provided repository.

---

## 🚀 Installation and Execution Steps

### 1. Clone the repository

```
git clone https://github.com/hiltonnery/concierge-digital-app.git
cd concierge-digital-app
```

### 2. Install the dependencies
```
npm install
```

### 3. Start the development server
```
npm run dev
```

### 4. Access the browser
```
http://localhost:5173
```
---

## 🧪 Test the Application

You can test the following features:

### 🔐 Test Login
- **Email:** admin@accenture.com
- **Code:** 123456

### ✅ Features Available for Testing
- Smart dashboard with interactive cards and AI search
- Speaker management with detailed modals and favorites system
- Lecture registration with vacancy control and filters by topic
- Personalized agenda and conflict visualization
- QR Scanner for networking and automatic check-in
- Profile card with QR Code for digital networking
- Categorized Help Center (FAQ) with smart search
- Responsive interface optimized for mobile and desktop

---

## 📌 Final Considerations

This project is an academic proof of concept that applies modern technologies to build automated service experiences in corporate events.

The code is available for learning, testing and future development purposes.
