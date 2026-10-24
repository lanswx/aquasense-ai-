# AquaSense AI

**AquaSense AI** is a hackathon prototype for presenting water-quality monitoring information on an interactive map, with Astana, Kazakhstan, as the demo area.

> **Prototype notice:** Map locations and any sample readings shown in this demo are illustrative. They are not verified environmental measurements and must not be used for health, safety, or regulatory decisions.

## Features

- Interactive map with zoom and pan controls
- Demo monitoring markers around Astana
- Links to view Astana in OpenStreetMap and Google Maps
- Browser-based interface; no build step is required

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Allow an internet connection so the map tiles and any external map data can load.

If your browser blocks some external map services, use the OpenStreetMap / Google Maps links provided below the map. Availability of third-party map tiles and data services is outside this project's control.

## Deploy with GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then save.
5. Wait for GitHub Pages to publish the site. The published URL will appear in the Pages settings.

## Tech stack

- HTML, CSS, JavaScript
- [Leaflet](https://leafletjs.com/) for interactive mapping
- [OpenStreetMap](https://www.openstreetmap.org/) and CARTO map tiles / external map services

## Data and limitations

- The prototype is a front-end demo, not a validated water-quality monitoring system.
- The map depends on external tile/data services and an internet connection.
- No live sensor feed or verified laboratory data is claimed by this repository.
- Before using this for real monitoring, connect a documented data source, show measurement timestamps and units, validate sensor accuracy, and clearly distinguish measured values from estimates.

## Roadmap

- [ ] Connect a documented, reliable water-quality data source
- [ ] Show units, timestamps, and data provenance for each measurement
- [ ] Add filtering by parameter and monitoring period
- [ ] Add accessible loading and error states
- [ ] Add screenshots of the working interface

## Contributing

Issues and pull requests are welcome. Please do not submit credentials, API keys, or private data.

## License

This project is released under the MIT License. See [`LICENSE`](LICENSE).
