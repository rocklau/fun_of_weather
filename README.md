# Weather & Climate Simulations

[中文版 (Chinese Version)](./README_CN.md)

A collection of interactive 3D weather and climate simulations built with
**Three.js**. These projects visualize complex atmospheric and oceanic phenomena
in a browser-based 3D environment.

## Projects

### 1. Cloud Simulator (`cloud.html`)

**"The Genealogy of Clouds: Wind Field & Evolution Visualization"**

An interactive simulation focusing on the life cycle of clouds and atmospheric
dynamics.

- **Cloud Evolution**: Visualize the transformation of clouds through different
  stages:
  - 💧 **Vapor**: Invisible water vapor rising from the ground.
  - ☁️ **Cumulus Humilis**: Fair-weather clouds.
  - 🥦 **Cumulus Congestus**: Towering cumulus clouds indicating instability.
  - ⛈️ **Cumulonimbus**: Mature storm clouds with anvils.
  - 🌊 **Stratocumulus**: Layered low clouds.
  - 🌫️ **Stratus**: Featureless low cloud sheets.
  - 🪶 **Cirrus Spissatus**: High-altitude ice clouds.
- **Wind Field System**: Dynamic visualization of air currents, turbulence, and
  wind shear using particle trails.
- **Interactive Plane**: A 3D plane model that reacts to atmospheric conditions
  (turbulence, updrafts).
- **Real-time Monitoring**: Dashboard showing vertical convection, horizontal
  wind shear, and altitude.

### 2. Ocean Climate System (`ocean_climate.html`)

**"Ocean Climate System - Continental Margin Simulation"**

A comprehensive simulation of the climate interactions at a continental margin,
featuring a day/night cycle and land-sea interactions.

- **Terrain & Ocean**: Realistic 3D terrain representing the deep ocean,
  continental slope, shelf, and coastal mountains.
- **Dynamic Climate Engine**:
  - **Day/Night Cycle**: Realistic sun movement affecting temperature.
  - **Land/Sea Breeze**: Simulates wind reversal based on the temperature
    difference between land and ocean.
  - **Water Cycle**: Visualizes evaporation, cloud formation, and precipitation.
  - **Upwelling**: Simulates nutrient-rich deep water rising to the surface.
- **Scenarios**:
  - **Normal**: Balanced climate with trade winds.
  - **Storm**: High energy state with heavy rain and strong winds.
  - **Drought**: High pressure, low evaporation, and dry conditions.
  - **Upwelling**: Strong offshore winds driving deep ocean upwelling.
- **Data Monitor**: Real-time gauges for evaporation rates, wind
  speed/direction, precipitation, and upwelling intensity.

### 3. Yang-Mills Spacetime Concepts (`space.html`)

**"Yang-Mills Spacetime Concepts - General Relativity & Quantum Field Theory
Visualization"**

An advanced visualization combining concepts from general relativity and quantum
field theory, demonstrating the interplay between spacetime curvature and gauge
fields.

- **Spacetime Curvature**: Dual-brane visualization showing:
  - **Black Hole**: Lower brane with gravitational singularity and spacetime
    depression.
  - **White Hole**: Upper brane with exotic matter and spacetime elevation.
  - **Wormhole Bridge**: Connecting tunnel between the two singularities.
- **Yang-Mills Gauge Fields**: Dynamic field lines representing non-Abelian
  gauge interactions:
  - Color-coded field lines (RGB) representing conceptual "color charge" in
    quantum chromodynamics.
  - Adjustable field strength affecting particle interactions.
- **Quantum Effects**:
  - **Hawking Radiation**: Particle emission near the black hole event horizon.
  - **Light Cones**: Visualization of causal structure in curved spacetime.
- **Gravitational Waves**: Ripples propagating through the spacetime fabric.
- **AI Physics Assistant**: Integrated Gemini-powered AI that explains the
  physics concepts in real-time.
- **Interactive Controls**: Adjust mass, spin, gauge field strength, and wave
  parameters via dat.GUI.

## Technologies Used

- **[Three.js](https://threejs.org/)**: 3D rendering engine.
- **[Tween.js](https://github.com/tweenjs/tween.js)**: Smooth animation
  transitions.
- **[dat.GUI](https://github.com/dataarts/dat.gui)**: Interactive control panel
  for `space.html`.
- **[Google Gemini API](https://ai.google.dev/)**: AI-powered physics
  explanations in `space.html`.
- **HTML5/CSS3**: UI overlays and layout.

## How to Run

These simulations run entirely in the browser with no build step required.

1. Clone or download this repository.
2. Open `index.html` in a modern web browser to access the main menu, or
   directly open:
   - `cloud.html` - Cloud Simulator
   - `ocean_climate.html` - Ocean Climate System
   - `space.html` - Yang-Mills Spacetime Concepts
3. **Note**: For the best experience, use a local web server (e.g., VS Code Live
   Server, `python -m http.server`) to avoid any potential CORS issues with
   texture loading, although these specific files primarily use procedural
   textures.

## License

MIT
