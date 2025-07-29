# 🧹 CleanZone – Civic Hygiene Reporting Web App

CleanZone is a full-stack civic-tech web application that allows users to **report unhygienic or neglected areas** (like garbage dumps, potholes, waterlogging) in their city by uploading photos and tagging the location. It uses **AI-based image classification** to auto-categorize the issue and routes it to concerned municipal departments or NGOs via a dashboard.

---

## 🚀 Features

- 📍 **Location Tagging:** Automatically detects user’s location or allows manual pin-drop.
- 📸 **Photo Upload:** Users upload images of the dirty area.
- 🧠 **AI Issue Detection:** Classifies issue (garbage, pothole, waterlogging, etc.) using image classification.
- 📊 **Admin Dashboard:** View reports, filter by type/status, mark issues as resolved.
- 🔔 **Email Notifications:** Sends updates to users and admins.
- 🛡️ **Auth System:** Separate login for users and civic authorities.
- 🌐 **Mobile-Responsive UI**

---

## 🛠️ Tech Stack

| Frontend       | Backend         | AI/ML Integration       | Database       | Other Tools         |
|----------------|------------------|--------------------------|----------------|----------------------|
| React.js       | Node.js + Express| Python (Flask) / TensorFlow.js | MongoDB        | Mapbox / OpenStreetMap, Multer |

---

## 🧠 AI Integration

- **Model Used:** Custom-trained CNN classifier for civic issues (e.g., trash, pothole, waterlogging).
- **Framework:** TensorFlow (Python) or TensorFlow.js for browser-based inference.
- **Training Dataset:** Built using scraped civic images + user contributions.

---

## 🧪 Installation

### 📦 Backend
```bash
cd server
npm install
node index.js

---

### Frontend
```bash
cd client
npm install
npm start


###🌍 Demo
Live URL: [Coming Soon]
Demo Video: [Coming Soon]







