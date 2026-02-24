# Travel Smart Map - Charlotte
A web map using **ArcGIS JavaScript API 5.0** and **Calcite Design System** to show points of interest in Charlotte, NC. Features:
- ArcGIS basemap switching
- Category-based points of interest (parks, coffee, hotels, etc.)
- Voice search for categories
- Distance calculation from map center
- Live weather info and 3-hour forecast
- Route link via Google Maps

## Setup

1. Clone the repository:

git clone https://github.com/YOUR_USERNAME/TravelSmartMap-Charlotte.git
cd TravelSmartMap-Charlotte

2. Replace your ArcGIS API key in index.html:
<script>var esriConfig={apiKey:"YOUR_ACCESS_TOKEN"};</script>

3. Open index.html in your browser (Chrome recommended).
How to Use
a. Use Map Controls panel to select a category (parks, coffee, etc.) or basemap.
b. Click the 🎤 Voice Search button and say “coffee”, “hotel”, “park”, “food”, or “gas station”.
c. Click on map markers to see weather, distance, and get route links.

4. Recommended places appear based on current time.
Folder Structure
• index.html → main web page
• assets/ → optional folder for additional JS or CSS
• .gitignore → ignore unnecessary files
Notes
• Requires internet to fetch ArcGIS modules and Open-Meteo API.
• Voice search uses browser SpeechRecognition (Chrome recommended).

![picture](https://github.com/0987poiuLKJH-Adnan/Travel-Smart-Map-Charlotte/blob/main/Screenshot%202026-02-24%20123105.png)
