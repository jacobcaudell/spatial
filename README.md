# Caudell Spatial Intelligence - 3D Visualization Portfolio

A showcase of cutting-edge 3D reconstruction and visualization technologies, featuring multiple architectural projects and rendering approaches.

## Projects

### Gasson Hall: Photogrammetry vs Neural Reconstruction
A comparison of classical photogrammetry (Metashape) and neural radiance fields (Nerfstudio) workflows using drone imagery from Boston College's Gasson Hall.

### St. Ignatius: Splat Rendering
Advanced splat rendering technology demonstrating real-time 3D visualization with unprecedented detail and performance.

## Overview

This portfolio demonstrates the evolution of 3D reconstruction technologies:
- **Classical Photogrammetry**: Traditional dense cloud generation and mesh reconstruction
- **Neural Radiance Fields**: AI-powered reconstruction using NeRF technology
- **Splat Rendering**: Cutting-edge real-time visualization with Gaussian splatting

## Deployment

This is a static website that can be deployed to any web hosting service:

### GitHub Pages
1. Push to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main`)

### Netlify/Vercel
1. Connect your repository
2. Build command: (none needed - static site)
3. Publish directory: `/` (root)

### Local Development
Simply open `index.html` in a web browser or serve with any local server:
```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

## Project Structure
```
spatial/
├── index.html              # Gasson Hall project page
├── st-ignatius.html        # St. Ignatius project page
├── style.css               # Shared styling
├── README.md               # This file
└── assets/
    ├── CSI_logo.png        # Company logo
    ├── gasson_metashape.mp4    # Metashape render video
    └── gasson_nerfstudio.mp4   # Nerfstudio render video
```

## Technical Details

- **Drone**: DJI Matrice 4 Enterprise
- **Processing**: Cloud H100 GPU instances
- **Software**: Metashape, Nerfstudio, Gaussian Splatting
- **Output**: High-resolution architectural flythroughs and real-time visualization

## License

© 2025 Caudell Spatial Intelligence
