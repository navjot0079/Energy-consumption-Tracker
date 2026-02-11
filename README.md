# ⚡ Smart Energy Dashboard – Green IT Tracker

A modern **Smart Energy & Sustainability Dashboard** that visualizes energy consumption, promotes eco-friendly habits, and helps users track their environmental impact.

Built using **HTML, CSS, JavaScript, and Chart.js**, this project demonstrates real-time API integration, interactive charts, and a clean responsive UI.

---

## 🌍 Features

### 📊 Energy Monitoring
- Fetches real energy consumption data from EIA API
- Weekly visualization using Chart.js
- Interactive line chart

### 💡 Energy Saving Tips
- Random sustainability tips generator
- Encourages eco-friendly habits

### 🏆 Leaderboard
- Displays users ranked by energy savings
- Gamification for motivation

### 🌱 Green IT Landing Page
- Modern responsive design
- Sustainability awareness sections
- Services & blog sections
- Call-to-action navigation

### 📱 Responsive Design
- Works on desktop, tablet, and mobile
- Clean card-based layout

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- Chart.js
- Fetch API
- Ionicons

---

## 📂 Project Structure

Smart-Energy-Dashboard/
│
├── index.html → Landing page (Green IT website)
├── tracker2.html → Energy dashboard page
├── assets/
│ ├── css/
│ ├── js/
│ └── images/
└── README.md


---

## 🚀 How to Run

### Option 1 – Simple
1. Download or clone the repo
2. Open `index.html` in browser
3. Click **Get Started** → opens dashboard

### Option 2 – Live Server (recommended)
If using VS Code:
1. Install **Live Server**
2. Right-click `index.html`
3. Click **Open with Live Server**

---

## 🔌 API Used

Energy data fetched from:

US Energy Information Administration (EIA) API

https://api.eia.gov/v2/electricity/rto/daily-region-data

You can replace the API key inside:

```js
const apiKey = 'YOUR_API_KEY';
