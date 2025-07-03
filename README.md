# Orca Encounters Map

A simple web application for reporting and visualizing orca‐boat interactions on an interactive ArcGIS map.

## Demo

Check out the live demo here:  
https://chadlanoway.github.io/Orca-Interaction/

## Features

- **Interactive Map**  
  - Ocean basemap with client‐side clustering  
  - Blue clusters for sightings, orange clusters for attacks  
- **Report Submission Form**  
  - Boat name, date, time, zone, damage description, remarks  
  - Click‐to‐select map coordinates or “Use My Location” via geolocation  
  - Photo upload (via REST `addAttachment` endpoint)  
- **Custom Popups**  
  - Attribute table + thumbnail gallery of attachments  
  - Wisconsin “Diversionary Tool” easter‐egg popup with embedded video  
- **Responsive UI**  
  - Slide‐out form panel  
  - Filter pill for event types  
  - Styled with Barlow Condensed font  

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/chadlanoway/orca-encounters-map.git
   cd orca-encounters-map
