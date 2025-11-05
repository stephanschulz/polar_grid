# Half Cylinder Room Simulator

Interactive 2D visualization tool for exploring polar coordinate systems with customizable tessellation and grid projections.

## 🔗 Live Demo

**[View Live Application →](https://stephanschulz.ca/polar_grid/)**

## Features

### Option 1: Dots on Polar Lines
- Adjustable outer and inner diameters
- Configurable circle resolution (segments)
- Variable polar lines per segment
- Dots with exponential spacing bias control
- Real-time dot count display

![Option 1: Dots on Polar Lines](images/Screenshot%202025-11-05%20at%204.58.58%20PM.jpg)

### Option 2: Curved Lines
- Semicircular curved lines connecting polar lines
- Exponential spacing bias for curve distribution
- Dots on curves with adjustable spacing
- Larger curves automatically have more dots based on arc length

![Option 2: Curved Lines](images/Screenshot%202025-11-05%20at%204.59.04%20PM.jpg)

### Option 3: Grid Projection
- Cartesian grid projected onto polar coordinate system
- Adjustable grid square size
- Toggle between all dots or only dots intersecting with polar lines
- Visualizes how rectangular grids map to curved surfaces

![Option 3: Grid Projection](images/Screenshot%202025-11-05%20at%204.59.11%20PM.jpg)

## Controls

All options share common controls:
- **Outer Ø**: Control the outer radius of the half-cylinder
- **Inner Ø**: Control the inner radius of the half-cylinder
- **Segments**: Define circle tessellation resolution (3-100)
- **Lines/Segment**: Add additional polar lines between segments

### Option-Specific Controls

**Option 1:**
- **Dots/Line**: Number of dots per polar line (0-20)
- **Dot Bias**: Exponential spacing distribution (-2 to 2)

**Option 2:**
- **Curved Lines**: Number of radial curve lines (0-20)
- **Curve Bias**: Exponential spacing for curves (-2 to 2)
- **Dot Spacing**: Distance between dots on curves (10-100px)

**Option 3:**
- **Grid Size**: Size of Cartesian grid squares (10-100px)
- **Only dots on polar lines**: Toggle to filter dots by polar line intersection

## Technical Details

- Built with vanilla JavaScript and HTML5 Canvas
- Real-time rendering with interactive controls
- Exponential spacing algorithms for natural distribution
- Compact two-column control layout
- Responsive design with glassmorphism UI

## Use Cases

- Visualizing polar coordinate transformations
- Understanding tessellation and discretization
- Exploring grid mapping on curved surfaces
- Educational tool for coordinate system concepts
- Design reference for curved architectural spaces

