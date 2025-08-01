# Gasson Hall Renders - Caudell Spatial Intelligence

A showcase of high-fidelity architectural visualization comparing classical photogrammetry (Metashape) and neural radiance fields (Nerfstudio) workflows.

## Overview

This project demonstrates two different approaches to 3D reconstruction from drone imagery:
- **Metashape Render**: Classical photogrammetry pipeline with dense cloud generation and mesh reconstruction
- **Nerfstudio Render**: Neural radiance field reconstruction using the same input dataset

Both renders originate from a single drone capture of Gasson Hall at Boston College.

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
├── index.html          # Main page
├── style.css           # Styling
├── README.md           # This file
└── assets/
    ├── CSI_logo.png    # Company logo
    ├── gasson_metashape.mp4    # Metashape render video
    └── gasson_nerfstudio.mp4   # Nerfstudio render video
```

## Technical Details

- **Drone**: DJI Matrice 4 Enterprise
- **Processing**: Cloud H100 GPU instances
- **Software**: Metashape, Nerfstudio, Blender
- **Output**: High-resolution architectural flythroughs

## License

© 2025 Caudell Spatial Intelligence
