# QuakeGuard  

**QuakeGuard** is a cutting-edge disaster simulation and preparedness tool that uses interactive maps and an AI-powered chatbot to help users understand and plan for natural disasters. The platform enables users to simulate disaster scenarios, visualize affected areas on a dynamic map, and receive personalized, location-based safety guidance in real time.  

---

## Features  

- **Disaster Simulation**:  
  Simulate earthquakes, floods, or hurricanes with customizable parameters like magnitude, impact radius, and location.  

- **Real-Time Location Awareness**:  
  Automatically detects your location (via GPS or IP fallback) to provide tailored safety advice and display impacted areas.  

- **Dynamic Map Visualizations**:  
  Use OpenStreetMap and Leaflet.js to display disaster zones, draggable markers for customizable locations, and radius overlays for affected areas.  

- **AI-Powered Assistance**:  
  The integrated chatbot answers user-specific queries like “Where is the nearest shelter?” or “What should I do during an earthquake?”  

- **Impact Analysis**:  
  Simulates affected populations (future improvement: integrating a free population API for accurate estimates).  

- **Responsive Design**:  
  Clean, user-friendly interface built with Tailwind CSS for a seamless experience across devices.  

---

## Tech Stack  

- **Frontend**: HTML, Tailwind CSS, JavaScript  
- **Mapping**: Leaflet.js with OpenStreetMap integration  
- **Geolocation**: HTML5 Geolocation API (with IP-based fallback)  
- **Chatbot**: AI-driven input box for real-time assistance  
- **Population Data**: Placeholder for API integration to provide population impact statistics  

---

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/gabriel-dalton/quakeguard.git  
   cd quakeguard  
   ```  

2. Open `index.html` in your browser to launch the application.  

---

## How It Works  

1. **Disaster Selection**:  
   - Users choose between earthquakes, floods, or hurricanes.  
   - The interface adapts based on the disaster type (e.g., magnitude input for earthquakes).  

2. **Interactive Map**:  
   - A draggable marker allows users to select their desired location.  
   - An impact radius is displayed based on user inputs.  

3. **Real-Time Guidance**:  
   - The chatbot answers critical queries like evacuation routes, nearest shelters, and safety protocols.  

4. **Impact Analysis**:  
   - The application estimates population impact within the disaster radius (with plans for future API integration to enhance accuracy).  

---

## Future Improvements  

- **Population Impact API**: Integrate a free API to calculate population impacts more accurately within a disaster zone.  
- **Real-Time Alerts**: Add live earthquake or weather alerts for dynamic updates.  
- **Evacuation Routes**: Incorporate route-mapping features for safe evacuations.  
- **Mobile Accessibility**: Develop a mobile-first version to ensure QuakeGuard is accessible on any device, anywhere.  
- **Advanced AI Assistance**: Expand chatbot functionality to provide even more in-depth guidance and real-time solutions during emergencies.  

---

## License  

This project is licensed under the [MIT License](LICENSE).  

---

## Acknowledgments  

- [Leaflet.js](https://leafletjs.com/) for interactive mapping functionality  
- [OpenStreetMap](https://www.openstreetmap.org/) for free and accessible map data  
- [Tailwind CSS](https://tailwindcss.com/) for elegant and responsive design   
- Created as part of the TKS Focus Build Hackathon 2024  