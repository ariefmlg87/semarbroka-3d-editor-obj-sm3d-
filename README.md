# Semarbroka 3D editor obj (sm3d)
A 3D model editor for Semarbroka Engine, supporting OBJ and SM3D model files for easy editing and integration.
editor 3d model sor semarbroka engine

🎨 Semarbroka 3D Mesh Editor

A lightweight, zero-dependency 3D mesh modeling and vertex manipulation tool built with Python & Tkinter.
Semarbroka 3D Mesh Editor gives creators, developers, and 3D enthusiasts direct control over 3D geometry. Powered natively by Python's built-in Tkinter library, it allows you to prototype low-poly assets, inspect vertex coordinates, and construct road grids from scratch without heavy external dependencies or bloated CAD suites.

✨ Key Features

• Interactive 3D Viewport: Navigate effortlessly with smooth Orbit, Pan, and Zoom camera controls. Toggle between Shaded Faces, Wireframe Edges, and Vertex Points in real time.
• Precision Vertex Inspector: Click any vertex directly in the 3D space and fine-tune its exact X, Y, and Z coordinates using the side inspector panel.
• Live Vertex Data Table: Monitor every single vertex ID and its spatial position (Pos X, Pos Y, Pos Z) in a clean, synchronized bottom data grid.
• Global Object Transformations: Quickly translate (Move), rotate, and scale your entire mesh with one-click transformation buttons.
• Built-in Primitive Generators: Jumpstart your scene with ready-to-use base meshes:
	• Cube (2x2x2)
	• Plane / Road Grid (4x4)
	• Pyramid
• Seamless File I/O & Undo/Redo: Import and export standard Wavefront (.obj) files effortlessly, backed by a full Ctrl+Z / Ctrl+Y history stack.

🕹️ Viewport Controls


Action	Control
Select Vertex	Left Click on vertex point
Orbit Camera	Right Click + Drag
Pan View	Middle Click + Drag
Zoom In / Out	Mouse Scroll Wheel
Undo / Redo	Ctrl + Z / Ctrl + Y


🛠️ Tech Stack

• Language: Python 3.x
• GUI & 3D Canvas Rendering: Tkinter (Python Standard Library — no heavy third-party GUI frameworks required)

🚀 Getting Started


Prerequisites

Make sure you have Python 3.8+ installed on your system. (Note: On some Linux distributions, you may need to install python3-tk via your package manager).

Installation & Running

1. Clone the repository:bash
git clone https://github.com
cd semarbroka-3d-mesh-editor
Gunakan kode dengan hati-hati.
2. Run the application:bash
python semarbroka_3d_editor.py
Gunakan kode dengan hati-hati.

📄 Supported Formats

• Wavefront OBJ (.obj)
• Semarbroka 3D Native Format (.sm3d)

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
<img width="1249" height="822" alt="semarbroka_3d_editor_1" src="https://github.com/user-attachments/assets/b12737be-5657-4eb6-927b-221b2981d1cb" />
<img width="1249" height="822" alt="semarbroka_3d_editor_2" src="https://github.com/user-attachments/assets/125cbbce-c5eb-408e-8d15-79e084cb73a8" />
<img width="1253" height="822" alt="semarbroka_3d_editor_3" src="https://github.com/user-attachments/assets/c628c4df-c77c-4600-bd6f-3cfb766b1097" />
