# 🏠 Urban Estate – Rental Web Application (Frontend)

## 📌 Overview
**Urban Estate** is a modern rental web application frontend that allows users to **discover rental properties through an interactive map**, view detailed property information, manage favorites, and **communicate in real time using chat**.

The application is built using **React, TypeScript, and Vite**, uses **Leaflet** for map-based property visualization, **WebSockets** for real-time chat functionality, and **Cypress** for end-to-end testing.  
This repository contains the **frontend implementation only**.

---

## 🎯 Problem Statement
Traditional rental platforms often lack:
- Intuitive location-based property discovery
- Real-time communication between users
- Fast, responsive, and scalable UI
- Automated testing for critical user flows

---

## 💡 Solution
Urban Estate provides:
- Interactive map-based rental exploration
- Clean, role-based UI flows (Admin / Owner / Tenant)
- Real-time chat using WebSockets
- Automated end-to-end testing using Cypress
- High-performance frontend with modern tooling

---

## ✨ Key Features
- 🗺️ Interactive rental map using **Leaflet**
- 📍 Location-based property discovery
- 🏡 Property listing & detailed view
- ❤️ Favorite property management
- 💬 Real-time chat support (WebSocket)
- 👤 Role-based UI flows (Admin, Owner, Tenant)
- ⚡ Fast builds with Vite + HMR
- 🧪 End-to-end testing with Cypress

---

## 🛠️ Tech Stack & Tooling

### Frontend
- **React 18**
- **TypeScript**
- **Vite**
- **Leaflet** (Maps & geolocation)
- **WebSocket API** (Real-time chat)

### Testing
- **Cypress** (End-to-End testing)

### Code Quality
- Type-aware ESLint configuration
- React & JSX runtime linting
- Strict TypeScript rules for scalability

---

## 🗺️ Map Integration (Leaflet)
- Displays rental properties as map markers
- Supports zooming and panning
- Marker popups show property summary
- Improves user experience through spatial navigation

---

## 💬 Real-Time Chat (WebSockets)
- Enables instant communication between users
- Persistent WebSocket connection
- Low-latency message exchange
- Frontend-only implementation

---

## 🧪 Testing with Cypress
The project uses **Cypress** for automated end-to-end testing to ensure application stability.

### Cypress Covers:
- Page routing & navigation
- Property listing rendering
- Map interactions
- Favorite property actions
- Chat UI behavior

This ensures reliable user flows and prevents regressions.

---

## 🏗️ Project Structure
src/
├── components/ # Reusable UI components
├── pages/ # Application pages
├── services/ # API & WebSocket services
├── hooks/ # Custom React hooks
├── types/ # TypeScript interfaces
├── assets/ # Images & static assets
├── cypress/ # Cypress E2E tests
├── App.tsx
├── main.tsx
└── index.css

yaml
Copy code

---

## ⚙️ Setup & Installation

### Prerequisites
- Node.js (v18+)
- npm or yarn

### Installation
```bash
git clone https://github.com/your-username/urban-estate-frontend.git
cd urban-estate-frontend
npm install
Run Development Server
bash
Copy code
npm run dev
Application runs at:

arduino
Copy code
http://localhost:5173
🧪 Run Cypress Tests
bash
Copy code
npx cypress open
or

bash
Copy code
npx cypress run
📸 Screenshots & Product Demo
Add project screenshots here (exported from PPT):

Home Page

Login / Signup

Property Listing

Property Details

Map View

Favorite Properties

Chat Interface

Admin / Owner / Tenant Dashboards

Example:

md
Copy code
![Home Page](./assets/screenshots/home.png)
![Map View](./assets/screenshots/map.png)
![Chat](./assets/screenshots/chat.png)
🌱 Future Scope
Backend integration

Authentication & authorization

Payment integration

Property comparison tool

Chat message persistence

Mobile responsiveness

Multi-intersection role management

👨‍💻 Contributors
Dhyan Agni
Venkat

Team Members (if any)

🏁 Conclusion
Urban Estate demonstrates a scalable, real-world frontend rental platform using React, TypeScript, real-time communication, interactive maps, and automated testing, making it suitable for smart housing and rental ecosystems.

📄 License
This project is developed for educational and demonstration purposes.

markdown
Copy code

---

## 🔥 Next (high-impact options)
I can now:
- 📸 Convert your **PPT → GitHub screenshots**
- 🧪 Write **sample Cypress test files**
- 📄 Create **backend + microservices README**
- 📌 Generate **resume bullets from this project**
- 🧠 Add **architecture diagram explanation**

Just tell me what you want next 👌
