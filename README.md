# GLSL Fluid Fractals

Interactive WebGL fractal visualizations with Navier-Stokes fluid dynamics simulation.

## 🌐 Live Demo

View the live visualization: [https://raymassie.github.io/glsl-fractals/](https://raymassie.github.io/glsl-fractals/)

## Features

### Fractal Patterns
- **Wave Pattern** - Original flowing wave pattern
- **Plasma Energy** - Electric plasma-like energy fields
- **Flow Field** - Dynamic vector field patterns
- **Organic Growth** - Biological, organic structures
- **Distortion Waves** - Rippling distortion effects
- **Spiral** - Rotating spiral formations
- **Voronoi** - Cellular Voronoi patterns
- **Noise Clouds** - Cloud-like noise formations

### 3D Stage Shapes
- **Sphere** - Classic spherical projection with hyperbolic/parabolic/elliptical modes
- **Plane** - Flat 2D plane
- **Cylinder** - Cylindrical projection
- **Torus** - Donut-shaped projection
- **Box** - Cubic projection
- **Cone** - Conical projection

### Visual Effects
- **Navier-Stokes Fluid Simulation** - Physically accurate fluid dynamics
- **Color Schemes** - Monochromatic, Analogous, Complementary, Triadic, Square, Rectangular
- **Blend Modes** - 14 blend modes (Normal, Multiply, Screen, Overlay, Soft Light, Hard Light, Color Dodge, Color Burn, Linear Dodge, Linear Burn, Vivid Light, Linear Light, Difference, Exclusion)
- **Bump Mapping** - Surface detail based on fractal patterns
- **Center-Axis Spin** - Vortex/blender rotation effect
- **Custom Masks** - Circle, Square, Rounded Square, Diamond, Hexagon, Star, Ellipse

### Controls
- **Fluid Dynamics**: Intensity, Flow Speed, Viscosity
- **Animation**: Time Speed, Spin Speed
- **Display**: Zoom, Curvature, Iterations, Brightness
- **Color**: Color Scheme, Color Range, Hue, Blend Mode, Blend Percentage
- **Lighting**: Light Brightness, Light Distance, Bump Strength
- **Stage**: Stage Shape, Display Mode (for Sphere), Mask Shape
- **Grid**: Show/Hide grid overlay

## Usage

Open `index.html` in a modern web browser with WebGL support, or visit the [live demo](https://raymassie.github.io/glsl-fractals/).

## Controls

### Mouse/Touch
- **Drag**: Rotate the fractal pattern
- **Touch**: Full touch support for mobile/tablet devices

### Control Panel
- All parameters are adjustable in real-time via the collapsible control panel
- Control sections can be collapsed/expanded
- Settings persist across page reloads

## Technical Details

- **WebGL 1.0** - Hardware-accelerated rendering
- **GLSL Shaders** - Custom fragment shaders for fractal generation and fluid simulation
- **Multi-Pass Rendering** - Framebuffers and ping-pong textures for fluid simulation
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Performance** - Device pixel ratio capped at 2x for mobile optimization

## Files

- `index.html` - Complete standalone application (all code in one file)

## Browser Compatibility

Requires a modern browser with WebGL support:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers with WebGL support
