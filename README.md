# STL File Viewer

A simple, web-based application for viewing 3D models stored in the STL file format. Built using HTML, CSS, and JavaScript with the Three.js library for 3D rendering.
![stl_cyc_social](https://github.com/user-attachments/assets/1d632466-5611-4713-920c-31cd97b2103e)

## Features

- [x] **Load STL Files:** Load models via drag-and-drop, using the "Open" button (📂), or loading a default preview model (>Test Preview Model<).
- [x] **3D Model Interaction:**
  - [x] **Rotate:** Click and drag the left mouse button / Use one finger touch drag.
  - [x] **Pan:** Click and drag the right mouse button / Use two finger touch drag.
  - [x] **Zoom:** Use the mouse wheel / Use pinch gesture.
- [x] **Viewing Options:**
  - [x] **Standard Views:** Switch between Front, Top, Right, Left, Back, and Bottom views.
  - [x] **Center View:** Automatically position the camera to focus on the model.
  - [x] **Grid:** Toggle the visibility of the ground grid.
  - [x] **Wireframe:** Toggle the wireframe representation of the model.
- [x] **Model Manipulation:**
  - [x] **Scale:** Adjust the model's size using a slider (Scale percentage is displayed).
  - [x] **Color:** Change the model's color using a built-in color picker.
- [x] **Information Display:**
  - [x] **Tooltip:** Shows the loaded filename and current dimensions (Width, Height, Depth) of the model in millimeters, updating dynamically as the model is scaled.
- [x] **Export:**
  - [x] **Save as JPG:** Save the current view of the model as a JPG image. The image includes an overlay with the filename and dimensions. Attempts to use the Web Share API on mobile devices for easier sharing, falling back to a direct download. The filename is automatically derived from the loaded STL file's name.
- [x] **Responsive Design:** Adapts to different screen sizes.
- [x] **Tip Button:** A button (☕) to open a PayPal donation link in a new tab.

## To Do

- [ ] **Support Additional File Formats:** Add functionality to load and view models in formats like 3mf, oltp, stp, step, svg, amf, obj.

## How to Use

1.  Open the `index.html` file in a web browser.
2.  Drag and drop an STL file onto the designated area, or click the "Open" button (📂) to select an STL file from your computer.
3.  Use the mouse controls and the buttons in the bottom navigation bar to interact with the model.

## Controls Summary

- **Left Mouse Button / One Finger Drag:** Rotate model.
- **Right Mouse Button / Two Finger Drag:** Pan view.
- **Mouse Wheel / Pinch Gesture:** Zoom in/out.
- **Bottom Navigation Bar:** Access file operations, view controls, scaling, color options, and tip button.
