# Holcim Digital Twin Builder

A web-based 3D digital twin builder for industrial sites using [three.js](https://threejs.org/).  
Drag and drop GLB models onto a real-world map, scale them to real dimensions, and interact with them using a professional sidebar UI.

## Features

- **Drag & Drop Models:** Add models from the sidebar library or import your own GLB files.
- **Real-World Scaling:** Models are scaled to match real dimensions for accurate visualization.
- **Transform Controls:** Move, rotate, and scale models interactively.
- **Camera Views:** Switch between perspective, orthographic, top, and front views.
- **Scene Management:** Clear scene, take screenshots, and manage model hierarchy.
- **Lighting & Shadows:** Adjust scene lighting and toggle shadows for realism.

## Usage

1. Open `templates/drag.html` in your browser.
2. Drag models from the sidebar onto the map.
3. Click a model to select and edit its properties.
4. Import new GLB models using the "Import Model" button.
5. Use the control panel for camera, scene, and help options.

## Folder Structure

```
static/
  css/
    main.css
  img/
    Holcim Logo.png
    Lafarge Map.png
  js/
    drag.js
  models/
    preheater.glb
    silo.glb
    Storage.glb
templates/
  drag.html
```

## Technologies

- [three.js](https://threejs.org/)
- HTML/CSS/JavaScript
