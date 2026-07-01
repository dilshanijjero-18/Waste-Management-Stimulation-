♻️ EcoSort — Smart Waste Management Simulation

    An AI-powered smart waste sorting system simulation built with pure HTML, CSS, and JavaScript.

EcoSort Banner HTML CSS JavaScript Chart.js SDG
📖 Overview

EcoSort is a browser-based simulation of an intelligent waste management system. It demonstrates how computer vision, IoT sensors, and automated decision engines can work together to classify waste, route it to the correct bin, and provide real-time analytics to municipality administrators.

    ⚠️ This is a prototype/demo — AI classification and sensor data are simulated. No real ML model or hardware is required.

✨ Features
🔍 Detect & Sort

    Upload a waste image (JPG, PNG, WEBP) via file picker or drag-and-drop
    Capture a photo directly using your device camera
    Simulated AI analysis with a visual loading state
    Detection results including:
        Waste type & category
        Hazardous / Biodegradable / Recyclable flags
        Confidence score with animated progress bar
        Disposal instructions
    Virtual sensor readings: Weight, Moisture, Conductivity, Toxicity
    Animated smart bin that opens for the detected waste type

📊 Admin Dashboard

    KPI cards: Total Waste Collected, Municipality Collected, Waste Sold, CO₂ Saved
    Bar chart — waste collected by type (kg)
    Donut chart — disposal method breakdown
    Line chart — 6-month collection trend
    Recent detections log table
    Bin status monitoring table

👤 Customer Portal

    Schedule Pickup tab
    Track Request tab
    Waste Tips tab

ℹ️ About / SDG

    System component breakdown
    UN Sustainable Development Goals alignment (SDG 11, 12, 13)

🗑️ Supported Waste Categories
# 	Type 	Emoji 	Recyclable 	Hazardous 	Biodegradable
1 	Cooking Waste 	🍳 	❌ 	❌ 	✅
2 	Plastic 	🧴 	✅ 	❌ 	❌
3 	Metal 	🔩 	✅ 	❌ 	❌
4 	E-Waste 	💻 	✅ 	✅ 	❌
5 	Biodegradable 	🌿 	❌ 	❌ 	✅
6 	Non-Biodegradable 	🚫 	❌ 	❌ 	❌
7 	Medical Waste 	🏥 	❌ 	✅ 	❌
8 	Bio-Hazardous 	☣️ 	❌ 	✅ 	❌
9 	Chemical-Hazardous 	⚗️ 	❌ 	✅ 	❌
🛠️ Tech Stack
Technology 	Purpose
HTML5 	Structure & layout
CSS3 	Styling, animations, responsive design
Vanilla JavaScript 	Logic, DOM manipulation, simulated AI
Chart.js v4.4.1 	Dashboard charts
Tabler Icons v2.44 	Icon set

No build tools, no frameworks, no backend — just a single .html file.
🚀 Getting Started
Option 1 — Open Directly

Just double-click waste_management_simulation.html in your file explorer. It opens in any modern browser with no installation required.
Option 2 — Local Server (recommended for camera access)

Camera capture requires a secure context (https:// or localhost). Serve locally with any of:

# Python
python -m http.server 8080

# Node.js
npx serve .

# VS Code
# Use the "Live Server" extension

Then open http://localhost:8080/waste_management_simulation.html.
📁 Project Structure

ecosort/
└── waste_management_simulation.html   # Single self-contained file
    ├── <style>                        # All CSS (variables, layout, animations)
    ├── <body>                         # HTML structure (4 views)
    └── <script>                       # All JS (AI sim, charts, camera, drag-drop)

🖥️ Screenshots
View 	Description
Detect & Sort 	Upload image → AI analysis → bin opens
Admin Dashboard 	KPIs, charts, tables
Customer Portal 	Pickup scheduling & tracking
About 	System overview & SDG alignment
🔧 How It Works

Image Upload / Camera
        ↓
  Simulated AI Model
  (random waste type)
        ↓
  Virtual Sensor Readings
  (weight, moisture, conductivity, toxicity)
        ↓
    Decision Engine
        ↓
  Correct Bin Opens + Level Increases
        ↓
  Dashboard Updated

The analyzeWaste() function orchestrates the full pipeline with a 2.2s simulated processing delay to mimic a real computer vision model.
📱 Responsive Design

EcoSort is fully responsive:

    Desktop — 2-column detection layout, side-by-side dashboard panels
    Tablet / Mobile — single-column stacked layout, 2-column KPI grid

🌱 SDG Alignment
Goal 	Focus
SDG 11 — Sustainable Cities & Communities 	Smart municipal waste infrastructure
SDG 12 — Responsible Consumption & Production 	Reducing landfill via sorting & recycling
SDG 13 — Climate Action 	CO₂ reduction tracking
🔮 Future Enhancements

    Integrate real AI model (e.g., Anthropic Claude Vision API or TensorFlow.js)
    Connect live IoT sensor data via WebSockets
    Persist detection history with localStorage or a backend
    Add user authentication for the admin dashboard
    Export dashboard data as CSV / PDF
    Multi-language support (i18n)
    PWA support for offline use

🤝 Contributing

    Fork the repository
    Create a feature branch: git checkout -b feature/your-feature
    Commit your changes: git commit -m 'Add your feature'
    Push to the branch: git push origin feature/your-feature
    Open a Pull Request

📄 License

This project is open source and available under the MIT License.
👤 Author

Built as a smart waste management simulation prototype.
Contributions and feedback welcome! 🌍

Made with 💚 for a cleaner planet
About
No description, website, or topics provided.
Resources
Readme
Activity
Stars
0 stars
Watchers
0 watching
Forks
0 forks
Releases
No releases published
Create a new release
Deployments 1

    github-pages 1 hour ago

Packages
No packages published
Publish your first package
Contributors 1

    @dilshanijjero-18
    dilshanijjero-18

Languages

    HTML 100.0% 

Footer
