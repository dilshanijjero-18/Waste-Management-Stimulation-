# ♻️ EcoSort — Smart Waste Management Simulation

> An AI-powered smart waste sorting system simulation built using **HTML, CSS, and JavaScript**.

![HTML](https://img.shields.io/badge/HTML5-Structure-orange?logo=html5)
![CSS](https://img.shields.io/badge/CSS3-Styling-blue?logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-Logic-yellow?logo=javascript)
![Chart.js](https://img.shields.io/badge/Chart.js-v4.4.1-red?logo=chartdotjs)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

**EcoSort** is a browser-based simulation of an intelligent waste management system that demonstrates how **Artificial Intelligence, Computer Vision, IoT sensors, and automated decision-making** can be used to improve municipal waste management.

The application simulates waste detection, sorting, smart bin operations, dashboard analytics, and customer services—all inside a single HTML file.

> **Note:** This project is a **simulation/prototype**. AI predictions and sensor readings are generated programmatically and do not require real machine learning models or hardware.

---

# ✨ Features

## 🔍 Smart Waste Detection

- Upload waste images
- Drag & Drop support
- Camera capture (localhost/HTTPS)
- AI processing animation
- Simulated AI classification
- Confidence score
- Waste category prediction
- Disposal instructions
- Animated smart bins
- Virtual sensor readings

### Simulated Sensors

- ⚖️ Weight
- 💧 Moisture
- ⚡ Conductivity
- ☣️ Toxicity

---

## 🗑 Supported Waste Categories

| Waste Type | Recyclable | Hazardous | Biodegradable |
|------------|------------|-----------|----------------|
| 🍳 Cooking Waste | ❌ | ❌ | ✅ |
| 🧴 Plastic | ✅ | ❌ | ❌ |
| 🔩 Metal | ✅ | ❌ | ❌ |
| 💻 E-Waste | ✅ | ✅ | ❌ |
| 🌿 Biodegradable | ❌ | ❌ | ✅ |
| 🚫 Non-Biodegradable | ❌ | ❌ | ❌ |
| 🏥 Medical Waste | ❌ | ✅ | ❌ |
| ☣️ Bio-Hazardous | ❌ | ✅ | ❌ |
| ⚗️ Chemical Hazardous | ❌ | ✅ | ❌ |

---

# 📊 Admin Dashboard

The administrator dashboard provides live analytics including:

- 📦 Total Waste Collected
- 🏙 Municipality Collection
- ♻️ Waste Sold
- 🌱 CO₂ Saved
- 📈 Monthly Collection Trend
- 📊 Waste Type Distribution
- 🍩 Disposal Method Breakdown
- 📋 Recent Detection Logs
- 🗑 Smart Bin Status Monitoring

---

# 👤 Customer Portal

Users can:

- Schedule waste pickup
- Track pickup requests
- View recycling tips
- Learn proper waste disposal methods

---

# 🌍 Sustainable Development Goals

EcoSort supports the following United Nations Sustainable Development Goals:

| SDG | Description |
|------|-------------|
| 🏙 SDG 11 | Sustainable Cities and Communities |
| ♻️ SDG 12 | Responsible Consumption and Production |
| 🌱 SDG 13 | Climate Action |

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 | Styling & Responsive Design |
| JavaScript | Logic & Simulation |
| Chart.js | Dashboard Charts |
| Tabler Icons | Icons |

---

# 📁 Project Structure

```
EcoSort/
│
├── waste_management_simulation.html
│
├── HTML Structure
├── CSS Styling
└── JavaScript Logic
```

Everything is contained inside a **single HTML file**.

No frameworks.

No backend.

No build tools.

---

# 🚀 Getting Started

## Option 1 — Open Directly

Simply open

```
waste_management_simulation.html
```

in any modern browser.

---

## Option 2 — Local Server (Recommended)

Camera functionality requires **localhost** or **HTTPS**.

### Python

```bash
python -m http.server 8080
```

### Node.js

```bash
npx serve .
```

### VS Code

Use the **Live Server** extension.

Open

```
http://localhost:8080/waste_management_simulation.html
```

---

# ⚙️ How It Works

```
Image Upload / Camera
        │
        ▼
 Simulated AI Analysis
        │
        ▼
 Virtual Sensor Readings
        │
        ▼
 Decision Engine
        │
        ▼
 Correct Bin Opens
        │
        ▼
 Dashboard Updates
```

The `analyzeWaste()` function simulates AI processing with approximately **2.2 seconds** of analysis time before displaying the results.

---

# 📱 Responsive Design

EcoSort is optimized for:

- 💻 Desktop
- 📱 Mobile
- 📟 Tablet

The layout automatically adapts to different screen sizes.

---

# 🔮 Future Enhancements

- Real AI image classification
- TensorFlow.js integration
- Claude Vision / Gemini Vision support
- Real IoT sensor integration
- LocalStorage support
- Database connectivity
- User Authentication
- Admin Login
- Export Reports (PDF / CSV)
- Dark Mode
- Multi-language Support
- Progressive Web App (PWA)
- Cloud Deployment

---

# 📸 Screenshots

Add screenshots here after deployment.

Example:

```
screenshots/
│
├── detect-page.png
├── dashboard.png
├── customer-portal.png
└── about-page.png
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👩‍💻 Author

**Dilshani J Jero**

Final Year Student

**Department of Computing and Cybersecurity**

School of Quantum Science, Computing & AI

Rathinam Global Deemed to be University

GitHub:
https://github.com/dilshanijjero-18

---

# ⭐ Show Your Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates future improvements.

---

## 💚 Made with HTML, CSS & JavaScript for a Cleaner Planet 🌍
