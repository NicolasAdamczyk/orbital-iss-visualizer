# Orbital ISS Tracker

**Real-time Satellite Tracking & 3D Visualization System**

## Overview
This project is a high-fidelity 3D web application designed to track the International Space Station (ISS) in real-time. By combining orbital mechanics models with modern web graphics, it provides an immersive way to visualize the ISS's current position, predicted path, and telemetry data.

## Key Features
- **Real-time Propagation**: Fetches live TLE (Two-Line Element) data and uses the SGP4 algorithm to calculate precise orbital positions.
- **3D Visualization**: Custom Earth model built with **Three.js**, featuring high-resolution textures, atmosphere scattering, and real-time lighting.
- **Dynamic Orbit**: Renders the future path of the ISS, accounting for Earth's rotation and orbital inclination.
- **Live Telemetry**: Dashboard showing altitude, ground speed, and exact lat/long coordinates.

## Tech Stack
- **Frontend**: React.js / Vite
- **3D Engine**: Three.js (React Three Fiber)
- **Math & Physics**: SGP4.js for orbital propagation
- **Styling**: Tailwind CSS

## Development

```bash
# Clone the repository
git clone [https://github.com/NicolasAdamczyk/orbital-iss-visualizer](https://github.com/NicolasAdamczyk/orbital-iss-visualizer)
