# 🌤️ Global Weather App

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Version](https://img.shields.io/badge/version-1.0.0-green.svg) ![Status](https://img.shields.io/badge/status-active-success.svg)

A premium, fast, and responsive weather application built with **Vanilla JavaScript**, **HTML5**, and **CSS3**. It provides real-time weather updates and 7-day forecasts for any location worldwide.

![Weather App Demo](demo.png)

## 🌟 Features

- **🌍 Global Search Capability**  
  Seamlessly search by **City Name** (e.g., *London, Tokyo*) or **Postal Code** (e.g., *380001, 10001*).
  
- **🗺️ Intelligent Geocoding Strategy**  
  Uses a robust dual-API system:
  1. **Primary**: Open-Meteo Geocoding API.
  2. **Fallback**: OpenStreetMap Nominatim API (ensures granular support for Indian pincodes and smaller regions).

- **📊 Comprehensive Weather Data**  
  - Real-time Temperature & Conditions
  - Humidity & Wind Speed
  - **7-Day Weekly Forecast**

- **🍃 Air Quality Monitoring**  
  Live AQI (Air Quality Index) updates with health impact categories (Good, Moderate, Unhealthy).

- **📱 Fully Responsive**  
  Optimized for Desktop, Tablet, and Mobile devices.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **APIs**:
  - [Open-Meteo](https://open-meteo.com/) (Weather Data)
  - [OpenStreetMap Nominatim](https://nominatim.org/) (Geocoding Fallback)

## 📁 Project Structure

```bash
📦 weather-app
 ┣ 📜 index.html      # Main Structure
 ┣ 📜 style.css       # Styling & Responsive Design
 ┣ 📜 script.js       # API Logic & UI Updates
 ┣ 📜 demo.png        # Screenshot for README
 ┗ 📜 README.md       # Documentation
```

## 🚀 Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/PATEL-BHAVIK2306005/Front-End-Weadher-Application-Via-Open-source.git
   ```

2. **Run Locally**
   - Simply open `index.html` in your web browser.
   - No build step or package installation required!

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
