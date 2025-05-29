# Languages / 语言

[English](README_EN.md) | [中文](README.md)

---

# Vector Space Explorer

An interactive vector visualization and calculation tool based on Three.js, helping users intuitively understand the geometric meaning and algebraic operations of vectors.

## Features

### 🎯 Core Functions

#### 1. Interactive Vector Visualization & Operations
- **Vector Creation & Modification**: Real-time creation and adjustment of vectors in 2D/3D space
- **Vector Addition Visualization**: Demonstrate the geometric meaning of vector addition through parallelogram law
- **Vector Subtraction Visualization**: Show geometric representation of vector subtraction
- **Scalar Multiplication**: Demonstrate the effect of scalars on vector magnitude and direction

#### 2. Vector Geometric Meaning Analysis
- **Dot Product Visualization**: 
  - Real-time calculation and display of dot product values
  - Show the relationship between dot product and vector projection
  - Visualize perpendicular projection lines
- **Cross Product Visualization**: 
  - Display the direction of cross product vector (right-hand rule)
  - Show the magnitude of cross product (parallelogram area)
  - Complete cross product representation in 3D space
- **Projection Visualization**: 
  - Projection of one vector onto another
  - Clear geometric representation and numerical calculation
- **Angle Display**: 
  - Real-time calculation of angles between vectors
  - Arc-shaped visual representation

### 🛠 Technical Features

- **2D/3D Mode Switching**: Support vector operations in both 2D and 3D space
- **Real-time Calculation**: All operation results update in real-time
- **Interactive Controls**: 
  - Mouse control for camera perspective
  - Numerical input boxes for precise vector adjustment
  - Color customization
- **Visual Enhancement**: 
  - High-quality rendering
  - Smooth animation effects
  - Clear labels and numerical displays

## Usage Instructions

### Quick Start

1. Open the `index.html` file directly in your browser
2. No dependencies required, ready to use immediately

### Interface Operations

#### Vector Controls
- **Coordinate Input**: Enter X, Y, Z coordinate values directly in the left panel
- **Color Settings**: Click color picker to customize vector colors
- **Mode Switching**: Click 2D/3D button to switch display mode

#### Vector Operations
- **Addition**: Click "Show Addition (A + B)" button to view vector addition result
- **Subtraction**: Click "Show Subtraction (A - B)" button to view vector subtraction result
- **Scalar Multiplication**: 
  1. Click "Scalar Multiplication" button
  2. Set scalar value
  3. Select the vector to operate on

#### Geometric Operations
- **Dot Product**: Click "Dot Product Visualization" to view projection relationship
- **Cross Product**: Click "Cross Product Visualization" to view perpendicular vector
- **Projection**: Click "Projection Visualization" to view vector projection
- **Angle**: Click "Angle Display" to view angle arc

#### Display Options
- **Grid**: Toggle coordinate grid display
- **Axes**: Toggle XYZ axis display
- **Origin**: Toggle origin marker display
- **Labels**: Toggle vector label display

### 3D Controls

- **Rotation**: Hold left mouse button and drag
- **Zoom**: Mouse wheel or two-finger zoom
- **Pan**: Hold right mouse button and drag

## Technical Implementation

### Technology Stack
- **Three.js**: 3D graphics rendering engine
- **HTML5/CSS3**: Modern web standards
- **ES6+ JavaScript**: Modular programming

### Key Features
- **ArrowHelper**: Use Three.js arrow helper objects to represent vectors
- **Dynamic Geometry**: Real-time generation of parallelograms, projection lines, and other geometric shapes
- **Canvas Textures**: Dynamic generation of vector labels and numerical displays
- **Material System**: Use emissive materials for enhanced visual effects

### Core Algorithms
- **Vector Operations**: Standard vector mathematics based on Three.js Vector3 class
- **Dot Product Calculation**: `A·B = |A||B|cosθ`
- **Cross Product Calculation**: `A×B = |A||B|sinθ n̂`
- **Projection Calculation**: `proj_B(A) = (A·B/|B|²)B`

## Browser Compatibility

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

Latest versions of modern browsers are recommended for the best experience.

## Educational Applications

This tool is particularly suitable for the following scenarios:

### 📚 Teaching Use
- **Linear Algebra Courses**: Visual teaching of vector operations
- **Geometry Learning**: Intuitive display of vector geometric meaning
- **Physics Teaching**: Vector representation of physical quantities like force and velocity

### 🎓 Learning Assistance
- **Concept Understanding**: Deepen understanding of abstract concepts through visualization
- **Practice Verification**: Verify manually calculated vector operation results
- **Exploration Discovery**: Observe patterns by adjusting parameters

## Extension Possibilities

- [ ] Support for more vectors (C, D, etc.)
- [ ] Add vector combination operations
- [ ] Export calculation results
- [ ] Save/load scene configurations
- [ ] Animation demonstration features
- [ ] Vector field visualization

## Copyright Information

This project is licensed under the MIT License and can be freely used and modified.

---

**Enjoy your visual learning journey with vector mathematics!** 🚀
