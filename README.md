# Citi Bike Station Map

An interactive web-based visualization of Citi Bike stations in New York City using Leaflet.js.

## Features

- Real-time station data from Citi Bike API
- Multiple map views (Street, Dark, Satellite)
- Station clustering for better performance
- Color-coded station markers indicating:
  - 🟢 Healthy stations
  - 🟡 Coming soon
  - 🔴 Empty stations
  - 🟠 Low bike availability
  - 🔵 Out of order stations
- Interactive controls:
  - Station search functionality
  - Zoom toggle
  - Layer controls
  - Marker clustering

## Technologies Used

- Leaflet.js for map visualization
- D3.js for data fetching
- Moment.js for time formatting
- MarkerCluster plugin for Leaflet
- Extra Markers plugin for custom markers
- OpenStreetMap and CARTO tile layers

## Getting Started

1. Clone the repository
2. Open `index.html` in a web browser
3. The map will automatically load with current Citi Bike station data

## Usage

- Click station markers to view station details
- Use the search bar to find specific stations
- Toggle different map layers using the layer control
- Use the control panel to:
  - Enable/disable zoom on click
  - Reset map view
  - Search for stations

## Data Source

Station data is fetched in real-time from the Citi Bike GBFS (General Bikeshare Feed Specification) API:
- Station Information: `https://gbfs.citibikenyc.com/gbfs/en/station_information.json`
- Station Status: `https://gbfs.citibikenyc.com/gbfs/en/station_status.json`