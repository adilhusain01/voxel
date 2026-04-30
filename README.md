# VoxelArt

VoxelArt is a browser-based voxelization experience for image-based 3D art. It turns uploaded images into interactive 3D voxel sculptures with visual controls for resolution, extrusion, spacing, material style, bloom, and explosion effects.

## Key Features

- Upload any image and convert it into a block-based 3D voxel composition
- Adjustable voxel resolution and height map extrusion
- Spacing controls for voxel packing and separation
- Multiple voxel shapes: box, cylinder, sphere, cone
- Material presets: matte, metal, glass
- Visual effects: bloom glow and explosion/deconstruct animation
- Screenshot capture and OBJ model download support
- Mobile-friendly responsive UI with touch controls

## Usage

1. Open `index.html` in a modern browser.
2. Click `Upload Image` and choose an image file.
3. Adjust the controls to customize resolution, height, spacing, shape, material, and effects.
4. Use the camera buttons to zoom and rotate the scene.
5. Capture a screenshot or download the generated model once available.

## Installation

No setup is required. The app is a single-page static web app built with native browser modules and Three.js.

1. Clone the repository.
2. Open `index.html` in your browser.

## Development

- `index.html` contains the full UI, Three.js scene setup, and voxelization controls.
- The app uses the Three.js `OrbitControls`, `OBJExporter`, and post-processing passes like `UnrealBloomPass`.
- The UI is styled with Tailwind CSS via CDN.

## Notes

- For the best experience, use a browser that supports ES modules and WebGL.
- Keep in mind that very high resolutions may be resource intensive in the browser.

## License

Use as needed for demos, prototypes, or portfolio projects.
