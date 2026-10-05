# SoleX Partners ☀️
> **Illuminating the Future of Solar Finance & Commercial Clean Energy Adoption**

[![Deploy static content to Pages](https://github.com/Shreyas-84524/Solex/actions/workflows/static.yml/badge.svg)](https://github.com/Shreyas-84524/Solex/actions/workflows/static.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/Live-GitHub%20Pages-brightgreen)](https://shreyas-84524.github.io/Solex/)

---

## 🌟 Overview

**SoleX Partners** is a B2B clean energy facilitation and financial modeling platform designed to streamline solar adoption for commercial enterprises, industrial facilities, and residential housing societies. 

During our hackathon, we identified a critical barrier in the green energy transition: **complexity and lack of objective guidance**. Businesses want to cut energy costs and reduce carbon footprints, but they get overwhelmed by opaque installer quotes, convoluted ROI projections, and subsidy regulations. At the same time, certified solar EPC (Engineering, Procurement, and Construction) contractors struggle to find qualified, high-intent leads.

**SoleX sits on the client's side of the table as an objective green energy facilitator**, removing the friction from solar financing, feasibility analysis, vendor discovery, and post-installation monitoring.

---

## 🚀 Key Features

### 1. 🧮 Interactive ROI & Installation Cost Calculator (`cost.html`)
- **Instant Area-Based Feasibility**: Calculate project payback periods and upfront CapEx estimates instantly by inputting available rooftop area (in sq meters).
- **Phased Cost Forecasting**: Detailed cost breakdown showing:
  - Pre-installation energy baseline
  - Estimated installation CapEx
  - First-year transitional utility expenses
  - 15+ months payback threshold (achieving near-zero operational electricity costs)
- **Localized Financial Modeling**: Currency formatting in INR with instant dynamic updates.

### 2. 📊 SoleX Edge — Investor & Enterprise Dashboard (`indexlogin.html`)
- **Executive KPI Monitoring**: Track CO₂ emission reductions, project timeline adherence, and lifetime savings at a glance.
- **Deep-Dive Analytic Views**:
  - **Project Work Tracker (`slide1.html`)**: Real-time deployment milestone tracking and phase scheduling.
  - **Expected Energy Savings Analytics (`slide2.html`)**: Dynamic yield tracking and cost-saving projections based on localized weather patterns and grid tariffs.
  - **Asset Information & Inventory (`slide3.html`)**: Live monitoring of commercial roof arrays, high-efficiency panel health, and central inverter uptime.

### 3. 🤝 Vetted Vendor & EPC Partner Portal (`vendor.html`)
- **B2B Partnership Network**: Connects clients with pre-screened, certified solar installers and EPC contractors.
- **Vendor Onboarding**: Integrated application pipeline capturing company credentials, service territories, and certifications.
- **High-Intent Lead Distribution**: Delivers vetted solar projects directly to contractors, reducing acquisition costs.

### 4. 🔔 Smart Alerts & Notifications Center (`notificationin.html`)
- Alerts for system audits, quarterly Solar Edge generation reports, and regulatory compliance deadlines (e.g., BRSR compliance).

### 5. 📚 Clean Energy Knowledge Hub (`blog1.html` – `blog4.html`)
- Educational resources addressing commercial solar feasibility, society rooftop installations, comprehensive energy audits, and vendor selection strategies.

---

## 🛠️ Technology Stack

- **Frontend**: Semantic HTML5, Modern CSS3 (CSS Variables, Flexbox, CSS Grid, Glassmorphic Design System), Vanilla JavaScript (ES6+)
- **Typography & Icons**: Inter, Poppins, EB Garamond via Google Fonts, Custom SVG Iconography
- **CI/CD & Hosting**: GitHub Pages automated deployment via GitHub Actions (`.github/workflows/static.yml`)

---

## 📂 Project Structure

```plaintext
Solex/
├── .github/
│   └── workflows/
│       └── static.yml          # GitHub Actions deployment to GitHub Pages
├── .nojekyll                   # Bypasses Jekyll processing for GitHub Pages
├── README.md                   # Project documentation
├── index.html                  # Landing page & hero showcase
├── index.css                   # Main global styles & responsive layouts
├── about.html & about.css      # Mission, vision, and team details
├── cost.html & cost.css        # Interactive ROI & cost estimation calculator
├── vendor.html & vendor.css    # EPC vendor partnership portal
├── contact.html & contact.css  # Contact & consultation request page
├── login.html & register.html  # User authentication & registration
├── indexlogin.html             # SoleX Edge Dashboard (Logged-in view)
├── indexlog.html & indexlog.css# Dashboard styling & analytics components
├── notificationin.html         # User notification center & alerts
├── notifications.html          # Alternate notifications view
├── slide1.html                 # Project deployment tracker module
├── slide2.html                 # Energy savings analytics module
├── slide3.html                 # Solar asset inventory & health module
├── blog1.html - blog4.html     # Knowledge base & educational articles
├── script.js                   # Client-side validation & interactive utilities
└── alex_carter.jpg             # Profile avatar asset
```

---

## ⚡ Getting Started Locally

Because SoleX is built purely with lightweight web standards, no complex build tools or dependencies are required.

### Prerequisites
- A modern web browser (Chrome, Edge, Firefox, Safari)
- Git installed on your system

### Installation & Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shreyas-84524/Solex.git
   cd Solex
   ```

2. **Open the project**:
   - Simply double-click `index.html` to open it in your browser, or
   - Use a lightweight local server (e.g., VS Code Live Server, or Python):
     ```bash
     # Using Python 3
     python -m http.server 8000
     ```
   - Navigate to `http://localhost:8000` in your browser.

---

## 🌐 Live Deployment (GitHub Pages)

The repository includes a automated GitHub Actions workflow configured under `.github/workflows/static.yml`. 

Every push to the `main` branch automatically triggers the pipeline:
1. Checks out the source code
2. Configures GitHub Pages environment
3. Uploads static build artifacts
4. Deploys live to **GitHub Pages**:
   👉 **[https://shreyas-84524.github.io/Solex/](https://shreyas-84524.github.io/Solex/)**

---

## 🎯 Hackathon Vision & Future Roadmap

- [ ] **AI-Powered Satellite Roof Mapping**: Integrate satellite imagery APIs to automatically assess rooftop usable area, tilt, and shading.
- [ ] **Automated EPC Bidding System**: Allow verified vendors to submit competing quotes directly within the platform.
- [ ] **IoT Inverter Integration**: Connect directly to solar inverter telemetry (e.g., SolarEdge, Enphase) for live generation telemetry and anomaly detection.
- [ ] **Carbon Credit Tokenization & Trading**: Enable commercial owners to quantify and monetize verified carbon credits.

---

## 📄 License

This project was developed for the hackathon and is licensed under the [MIT License](LICENSE).
