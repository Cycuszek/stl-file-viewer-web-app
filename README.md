# STL File Viewer

A simple, web-based application for viewing 3D models stored in the STL file format. Built using HTML, CSS, and JavaScript with the Three.js library for 3D rendering.

## Features

- **Load STL Files:** Load models via drag-and-drop or by using the "Open" button.
- **3D Model Interaction:**
  - **Rotate:** Click and drag the left mouse button.
  - **Pan:** Click and drag the right mouse button.
  - **Zoom:** Use the mouse wheel.
- **Viewing Options:**
  - **Standard Views:** Switch between Front, Top, Right, Left, Back, and Bottom views.
  - **Center View:** Automatically position the camera to focus on the model.
  - **Grid:** Toggle the visibility of the ground grid.
  - **Wireframe:** Toggle the wireframe representation of the model.
- **Model Manipulation:**
  - **Scale:** Adjust the model's size using a slider (Scale percentage is displayed).
  - **Color:** Change the model's color using a built-in color picker.
- **Information Display:**
  - **Tooltip:** Shows the current dimensions (Width, Height, Depth) of the model in millimeters, updating dynamically as the model is scaled.
- **Export:**
  - **Save as JPG:** Save the current view of the model as a JPG image. The filename is automatically derived from the loaded STL file's name.
- **Responsive Design:** Adapts to different screen sizes.

## How to Use

1.  Open the `index.html` file in a web browser.
2.  Drag and drop an STL file onto the designated area, or click the "Open" button (📂) to select an STL file from your computer.
3.  Use the mouse controls and the buttons in the bottom navigation bar to interact with the model.

## Controls Summary

- **Left Mouse Button + Drag:** Rotate model.
- **Right Mouse Button + Drag:** Pan view.
- **Mouse Wheel:** Zoom in/out.
- **Bottom Navigation Bar:** Access file operations, view controls, scaling, and color options.
