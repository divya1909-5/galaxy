# 3D Solar System Simulation

A web-based interactive 3D simulation of our solar system built with Three.js.

## Features

- **Realistic 3D rendering** of the Sun and 8 planets with relative sizes and distances
- **Interactive controls** to adjust the speed of each planet's orbit
- **Zoom and rotation** using mouse controls (orbit controls)
- **Click on planets** to view information and automatically focus the camera
- **Responsive design** that works on desktop and mobile devices
- **Light/dark mode** toggle for better viewing in different environments
- **Pause/resume** the simulation
- **Reset view** to default camera position
- **Zoom feature** - Use mouse wheel to zoom in/out on planets and the Sun
- **Dynamic lighting** with the Sun as a light source
- **Visual effects** including Sun glow and corona
- **Saturn's rings** rendered realistically

## Technologies Used

- Three.js (3D rendering library)
- HTML5, CSS3, JavaScript

## How to Use

1. Open the `index.html` file in a modern web browser
2. Use your mouse to:
   - Left-click and drag to rotate the view
   - Right-click and drag to pan
   - Scroll wheel to zoom in and out
3. Click on any planet or the Sun to view information and automatically focus the camera
4. Use the control panel to:
   - Pause/resume the simulation
   - Toggle between light/dark mode
   - Reset the view to default
   - Adjust the orbital speed of each planet using sliders

## Customization

You can easily modify the simulation by editing the `planetsData` array in the JavaScript code. Each planet has properties you can adjust:

- `size`: Relative size of the planet
- `distance`: Distance from the Sun
- `orbitSpeed`: Base speed of orbit
- `rotationSpeed`: Speed of planet's rotation
- `color`: Planet color
- `info`: Information displayed when clicked

## Performance Notes

For best performance:
- Use a modern browser with WebGL support (Chrome, Firefox, Edge, Safari)
- On mobile devices, the simulation may be less smooth due to hardware limitations
- Reducing the number of stars in the background can improve performance on slower devices

## Future Enhancements

Potential improvements could include:
- Adding moons for planets that have them
- More detailed planet textures
- Asteroid belt between Mars and Jupiter
- Comets with elliptical orbits
- Scale-accurate distances (currently compressed for better visualization)
- Time controls (speed up/slow down entire simulation)

## License

This project is open source and available under the MIT License.
