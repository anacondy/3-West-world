# 🌍 Western World Political Dashboard 2025

[![Live Site](https://img.shields.io/badge/Live%20Site-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://anacondy.github.io/3-West-world/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

> **Interactive political map dashboard showing the current governance landscape of Western democracies**

🔗 **[View Live Site →](https://anacondy.github.io/3-West-world/)**

---

## 📸 Screenshots

### Desktop View
![Desktop View](https://github.com/user-attachments/assets/8c2ec51b-51fa-4706-9340-49af71ac4cb0)

### Mobile View
![Mobile View](https://github.com/user-attachments/assets/a2ab0449-d011-4b9b-b0db-37ad584ff2c0)

The site features an optimized mobile experience with a bottom panel that appears when tapping on countries, taking only 30-40% of the screen for better usability.

---

## ✨ Features

- **Interactive Map**: Click/tap on countries to view detailed political information
- **Real-time Data**: November 2025 political landscape data
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Glassmorphism UI**: Modern, sleek interface with blur effects
- **Smooth Animations**: GPU-accelerated transitions for seamless experience
- **Touch-Friendly**: Swipe gestures support for mobile users
- **Cross-Browser Support**: Works on Chrome, Firefox, Safari, and Edge

---

## 🗺️ Countries Covered

| Region | Countries |
|--------|-----------|
| **North America** | USA, Canada |
| **Europe** | United Kingdom, Germany, France, Italy, Spain, Poland, Netherlands, Sweden, Norway, Ireland |
| **Oceania** | Australia, New Zealand |

---

## 📊 Data Transparency

### Data Sources
- Government official websites and press releases
- International news agencies (Reuters, AP, AFP)
- Electoral commission data from respective countries

### Knowledge Cutoff
- **Last Updated**: November 2025
- **Data Version**: November 2025 Edition
- **Coverage Period**: Latest election results and government formations as of November 2025

### Political Classification
| Code | Classification | Color |
|------|----------------|-------|
| P | Progressive | 🔵 Blue (#00ccff) |
| C | Conservative | 🔴 Red (#ff3333) |
| L | Centrist | 🟢 Green (#00ff99) |

---

## 🧪 Testing Information

### Last Tested
- **Date**: November 2025
- **Status**: ✅ All features working

### Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 120+ | ✅ Fully Supported |
| Firefox | 120+ | ✅ Fully Supported |
| Safari | 17+ | ✅ Fully Supported |
| Edge | 120+ | ✅ Fully Supported |
| Mobile Safari (iOS) | 17+ | ✅ Fully Supported |
| Chrome Mobile | 120+ | ✅ Fully Supported |

### Device Testing

| Device Type | Aspect Ratio | Status |
|-------------|--------------|--------|
| Desktop (1920x1080) | 16:9 | ✅ Optimized |
| Laptop (1366x768) | 16:9 | ✅ Optimized |
| Tablet (768x1024) | 3:4 | ✅ Optimized |
| iPhone 14 Pro | 19.5:9 | ✅ Optimized |
| Samsung Galaxy S23 | 20:9 | ✅ Optimized |
| Standard Mobile | 16:9 | ✅ Optimized |

### Features Tested
- [x] Map loading and rendering
- [x] Country selection and highlighting
- [x] Sidebar/bottom panel display
- [x] Smooth animations and transitions
- [x] Touch gestures (tap, swipe)
- [x] Responsive layout adjustments
- [x] Close button functionality
- [x] Cross-browser compatibility

---

## 🚀 Performance Optimizations

- **Preconnect**: DNS prefetching for external resources
- **Canvas Rendering**: Uses Leaflet's canvas renderer for better mobile performance
- **GPU Acceleration**: CSS `will-change` and `transform` for smooth animations
- **Debounced Events**: Optimized resize and scroll handlers
- **Passive Event Listeners**: Non-blocking touch event handling
- **Dynamic Viewport Units**: Uses `dvh` for accurate mobile viewport sizing

---

## 🛠️ Technology Stack

- **Mapping**: [Leaflet.js](https://leafletjs.com/) v1.9.4
- **Tiles**: [CARTO Dark Matter](https://carto.com/basemaps/)
- **Fonts**: [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts
- **GeoJSON**: World boundaries data

---

## 📖 Wiki / Documentation

### How It Works

1. **Map Initialization**: The app loads a dark-themed world map using Leaflet.js
2. **Data Layer**: GeoJSON country boundaries are loaded and styled based on political data
3. **Interactivity**: Users can click/tap countries to view detailed information
4. **Responsive Panel**: 
   - **Desktop**: Right sidebar slides in from the edge
   - **Mobile**: Bottom panel slides up from the bottom (30-40% of screen)

### Updating Data

To update political data, modify the `db` object in `index.html`:

```javascript
const db = {
    "CountryName": { 
        code: "P|C|L",           // P=Progressive, C=Conservative, L=Centrist
        flag: "🏳️",              // Country flag emoji
        leader: "Leader Name",   // Current head of government
        party: "Party Name",     // Ruling party
        gov: "Government Type",  // e.g., "Majority", "Coalition"
        seats: {g: 0, t: 0},     // Government seats / Total seats
        desc: "Description..."   // Brief political description
    }
};
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

<p align="center">
  Made with ❤️ for political transparency
</p>
