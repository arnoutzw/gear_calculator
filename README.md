# Involute Gear Generator

A professional gear design tool for creating involute gears with DXF and SVG export for CAD and CNC manufacturing.

## Features

- **Gear Design Options**:
  - Single gear generation
  - Gear pair (meshing gears) generation
- **Customizable Parameters**:
  - Module (size of teeth)
  - Tooth count
  - Pressure angle (typically 20° or 25°)
  - Profile shift for custom gear ratios
  - Bore diameter for shaft mounting
  - Clearance coefficient
  - Profile resolution for accuracy
- **Involute Profile Calculation**: Accurate mathematical computation of involute tooth profiles
- **Real-time Visualization**:
  - Live preview with pitch and base circles
  - Canvas-based rendering for instant feedback
- **Export Formats**:
  - **DXF** - For CAD software compatibility (AutoCAD, Fusion 360, etc.)
  - **SVG** - For web and vector editing
- **CNC Ready**: Generate files directly suitable for CNC machining
- **Professional Quality**: Adherence to gear design standards

## Tech Stack

- **HTML5** - Semantic markup
- **JavaScript** - Gear mathematics and generation algorithms
- **Canvas** - 2D visualization and preview
- **SVG** - Scalable vector export
- **PWA** - Progressive Web App capabilities

## Getting Started

### Online Demo
Visit the live application: [https://arnoutzw.github.io/gear_calculator/](https://arnoutzw.github.io/gear_calculator/)

### Local Installation
Simply open `index.html` in a modern web browser. No build tools or dependencies required.

### Usage
1. Open the application in your browser
2. Enter gear specifications:
   - Module (mm)
   - Number of teeth
   - Pressure angle
   - Profile shift
   - Bore diameter
3. View real-time preview of the gear design
4. Export as DXF for CAD software or SVG for vector editing
5. Use generated files for CNC machining or 3D printing

## Tips

- Standard pressure angles: 20° (common) or 25° (alternate)
- Module values: 0.5-10 mm (smaller = finer teeth)
- Profile shift allows for custom gear ratios without changing tooth count
- Increase profile resolution for smoother curves on high-precision applications

## Browser Support

Requires a modern browser with Canvas support (Chrome, Firefox, Edge, Safari)

## License

MIT License - See LICENSE file for details
