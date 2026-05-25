# AeroMesh

<p align="center">
  <img src="Pictures/y1rs.png" alt="Colnago Y1Rs Showcase" width="500" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Model--Viewer-333333?style=flat" alt="Model-Viewer" />
</p>

> An interactive 3d implementation showcasing the precision engineering and aerodynamics of the Colnago road bikes.

## Features


| Feature | Description |
|:---|:---|
| **Interactive 3D Model** | Rotatable, zoomable, and scalable rendering of the bike's frame |
| **Annotation Hotspots** | Clickable layout markers pinpointing specific bike components |

## Project Structure

```text
colnago-y1rs/
├── Models/
│   └── y1rs.glb              # 3d bike model
├── Pictures/                 # assets
│   ├── colnago_logo.png      
│   ├── leftmouseclick.png    
│   ├── rightmouseclick.png
|   ├── scrollbutton.png
│   └── y1rs.png
├── index.html                # Main file
├── LICENSE                  
└── README.md                
```

## Running the Project Locally

Because this project imports a local 3d `.glb` asset, most browsers will block the model from loading if you double-click the `index.html` file directly due to CORS security rules. 

To view it properly, you must run it through a local web server:

1. Open this project folder in **VS Code**.
2. Click the **Go Live** button at the bottom right corner (requires the **Live Server** extension).
3. The project will open at `http://127.0.0.1:5500` in your web browser.
