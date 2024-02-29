Project Goal: Develop a C++ application for viewing 3D wireframe models from .obj files, allowing various manipulations and visualizations.

Key Features:

- Model Loading: Loads .obj files, supporting vertices and surfaces lists.
- Object Transformations:
- Translation (X, Y, Z axes)
- Rotation (X, Y, Z axes)
- Scaling

Graphical User Interface (GUI):
- Model selection button and filename display
- Visualization area for the model
- Controls for translation, rotation, and scaling (buttons and input fields)
- Model information (filename, vertex/edge count)
- Performance: Handles models with various vertex counts (up to 1 million) efficiently.
- Projection customization (parallel, central)
- Customizable edge settings (type, color, thickness, display method)
- Customizable vertices (color, size)
- Selectable background color
- Settings persistence (saved across restarts)
- Screenshot capture (BMP, JPEG)
- Screencast recording (GIF animation)

Design Patterns: Utilizes MVC, Facade, Strategy, Singleton, Observer.

Technical Details:

Programming Language: C++ (C++17 standard)
Coding Style: Google style guide
Build System: Makefile (standard GNU targets)
Unit Testing: Comprehensive unit testing for model loading and affine transformations
Namespace: s21

This project provides a detailed description of the objectives, functionalities, and technical requirements for developing a 3D viewer application in C++. 