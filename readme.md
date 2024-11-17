# QuakeGuard

**QuakeGuard** is an interactive and educational emergency preparedness tool designed to simulate earthquake scenarios, provide real-time geolocation-based safety instructions, and visualize the impact radius on a dynamic map. By integrating free mapping APIs, the project helps users understand potential disaster impacts, identify nearby affected areas, and access actionable safety steps to stay prepared during emergencies.

---

## Features

- **Earthquake Simulation**: Simulate earthquake scenarios with customizable parameters like magnitude and impact radius.
- **Real-Time Location Awareness**: Leverage geolocation to provide location-specific emergency information.
- **Dynamic Map Visualizations**: Display affected zones and safety instructions using open-source mapping tools.
- **Emergency Instructions**: Offer actionable steps to prepare and respond during disasters.
- **Resource Integration**: Link to trusted emergency services and educational resources, such as FEMA and Ready.gov.

---

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Mapping**: OpenStreetMap & Leaflet.js
- **Geolocation**: HTML5 Geolocation API
- **Backend (Optional)**: Node.js (for simulation customization or storing user interaction data)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gabriel-dalton/quakeguard.git
   cd quakeguard
   ```

2. Open `index.html` in your browser to view the application.

---

## How It Works

1. **Simulate Earthquake**:
   - The user inputs parameters like magnitude and epicenter location.
   - A visual representation of the affected area is displayed on the map.

2. **Get Emergency Guidance**:
   - Location-based safety instructions are provided to users.
   - Quick links to resources like FEMA and local disaster management services.

3. **Educate and Prepare**:
   - Access preparedness steps for before, during, and after an earthquake.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- [Leaflet.js](https://leafletjs.com/) for the mapping library.
- [OpenStreetMap](https://www.openstreetmap.org/) for free maps.
- [Ready.gov](https://www.ready.gov/) and [FEMA](https://www.fema.gov/) for emergency preparedness resources.
- Inspiration from the TKS Focus Build Hackathon 2024.