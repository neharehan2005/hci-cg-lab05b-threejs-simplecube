# React Three.js Rotating Cube

This project demonstrates a simple 3D rotating cube using **Three.js** in a **React** application. It covers the basics of integrating Three.js with React using functional components and hooks.

## Features

* Renders a 3D cube with **rotation animation**.
* Responsive design: automatically adjusts to **window resizing**.
* Clean React setup using **functional components** and **useRef** / **useEffect** hooks.
* Basic scene setup with **camera**, **renderer**, and **mesh**.


## Project Structure

* `Cube.jsx` – Contains the main cube component.
* `App.jsx` – Renders the Cube component.


## How It Works

1. **Scene**: A Three.js `Scene` is created to hold all 3D objects.
2. **Camera**: A `PerspectiveCamera` is used to view the scene.
3. **Renderer**: `WebGLRenderer` renders the scene to the DOM.
4. **Cube**: A `BoxGeometry` mesh with `MeshBasicMaterial` forms the cube.
5. **Animation**: `requestAnimationFrame` rotates the cube continuously.
6. **Resize Handling**: The renderer and camera update automatically on window resize.
7. **Cleanup**: On component unmount, event listeners are removed, and the renderer is disposed to free memory.

🚀 Live Demo


https://hci-cg-lab05b-threejs-simplecube.vercel.app/


