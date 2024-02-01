## 🧊 Web Render Engine for 3D Assets - 3D Gaussian Splats & more! ✨
#### Created by: Michael Jernil, 3D Graphics Engineer & Enthusiast (https://www.linkedin.com/in/michael-jernil/) as Part of a Blog post to be released soon on www.radiancefields.com 
#### Blog Post: " Understanding 3D Gaussian Splatting ✨ through the lens of Render Engine - First Principles! " (Link will be added on Release)

### Demo
#### https://webrenderengine.vercel.app/
[scrnli_20_12_2023_17-47-17.webm](https://github.com/mikejernil/renderengine-basics/assets/43872457/21c8923b-b94e-4420-8ef6-fde7d94313ea)

#### Created w/ `React + TypeScript + Vite` using Libraries - `React Three Fiber + Three.js + luma-web`

#### DISCLAIMER: This Repo is currently a Work-In-Progess (at it's initial stages). More updates will be Coming soon!

### Features ⭐️
- View 3D Gaussian Splats generated using Luma AI (https://lumalabs.ai/)
- View glTF Assets
- Gizmo for Easy Navigation
- Deployed Vercel App

### Work in Progress 🚀
- View **Huge-scale 3D Textured Meshes** (3D Tiles) streamed from cloud (or) local storage
- View **Huge-scale Point Clouds** (Potree) streamed from cloud (or) local storage
- Enable Viewing of local/hosted **SPLAT** files
- Enable Viewing of local/hosted **glTF** files
- Support for setting up interactive 3D scenes with SPLAT, glTF & other types of 3D assets in the same space!
- More Sample assets! 🏗️
- UI Enhancements 😇

### Render Engine - First Principles 🧊
<img width="855" alt="Screenshot 2024-02-01 at 12 07 41 PM" src="https://github.com/mikejernil/web-render-engine/assets/43872457/71404259-71a3-4aa2-be08-3f174e5c1cda">


### 3D Gaussian Splatting through Render Engine - First Principles ✨
<img width="855" alt="Screenshot 2024-02-01 at 12 16 41 PM" src="https://github.com/mikejernil/web-render-engine/assets/43872457/8c19c7dd-9253-43c9-a45d-0a3fc80a2c2d">


With the latest advancements in Computer Graphics, there is a new Pandora's box that has been opened called - **'3D Gaussian Splatting'**. It works on the concept that real world scenes could be efficiently represented as 3D Gaussian Splats (3DGS) - as an alternative to Traditional Mesh representation which involves - Mesh, Textures, Lighting etc.

This 3DGS representation has the primary advantage that huge real-world scenes which are otherwise generated by classic photogrammetry & complex to render using traditional computer graphics techniques can now be represented as 3D Gaussian Splats, which you can imagine as 3D paint strokes with a centered color and transparency values around the center, which also takes into account from where/how the scene is being viewed (aka the Camera). When multiple of these strokes are rendered with proper blending of alpha transparency from each splat, it can form a near realistic 3D image that can be viewed from any angle. 🔮 

## Get Started 📺
### Clone Repo
Use `git clone <repo-link>` to clone the repo to your PC

### Install the Packages
Use `npm i` to install the necessary packages

### Run the 3D Viewer
Use `npm run dev` to run the viewer in development mode

### Viewer
Now you can see the Render Engine running on `http://localhost:5173`. You can navigate, interact & play around with the 3D Assets!

### Follow 👥
- **What The Graphics!** Blog for Simple resources on Computer Graphics ⭐️
  - LinkedIn (https://www.linkedin.com/company/98858074/)
- **Radiance Fields** Blog for anything new on Radiance Fields (NeRFs & Gaussian Splatting!).
  - LinkedIn (https://www.linkedin.com/company/radiancefields/) & Website (www.radiancefields.com)
- LinkedIn - https://www.linkedin.com/in/michael-jernil/
- Twitter/X - https://twitter.com/jernil_dev

